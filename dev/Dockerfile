FROM ubuntu:noble-20260210.1

ARG USERNAME=vscode
ARG USER_UID=1000
ARG USER_GID=$USER_UID

RUN apt-get update && \
    apt-get -y install m4 build-essential \
    autoconf opam libunwind-dev pkg-config git

RUN useradd -ms /bin/bash vscode
WORKDIR /home/vscode
USER vscode

RUN opam init --yes --bare && \
    opam update -a && \
    opam switch create default 5.4.0 --yes && \
    eval $(opam env)

RUN opam install --yes \
    ocaml-lsp-server odoc ocamlformat \
    utop async \
    core js_of_ocaml js_of_ocaml-ppx  stdio \
    merlin ocp-indent

RUN opam clean -a --yes

RUN echo 'eval $(opam env)' >> /home/vscode/.bashrc