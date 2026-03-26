## Learn OCaml Workshop 2026

### Introduction to Functional Programming in OCaml

This workshop will help learn the basics of programming in OCaml by solving a
set of exercises [original source](https://github.com/kayceesrk/learn-ocaml-workshop-2024)

Pre-requisites:
- [Docker](https://docs.docker.com/get-started/get-docker/)
- [Visual Studio Code](https://code.visualstudio.com/Download)
- [Git](https://git-scm.com/install)

Instructions for participants:
1. Clone the repository with exercises with:
    `git clone  https://github.com/fplaunchpad/learn-ocaml-workshop-2026`

2. Start Docker

3. Open Visual Studio, then navigate to "File -> Open Folder...

4. Open the directory cloned in step 1.

5. Click "Reopen in Container" when prompted

6. A VS Studio Terminal instance should open with the `exercises` folder.

7. Please navigate to each numbered folder containing an exercise and run:
   `dune runtest`.

   There are functions deliberately left incomplete for you to fill in. Before
   you do this, `dune runtest` will indicate where the error originates.

   After you successfully fill in the needed function, `dune runtest` will
   **not** show any output. This means that you have passed all tests for that
   problem successfully.

   Look at the errors indicated for each exercise and open the corresponding
   `problem.ml` file for look where the error can be.

   All exercises (except the first) have a `.mli` file which show the types for
   each function you are required to complete in order for the tests to pass.
   Read through the definitions in the `.mli` file if you need to help thinking
   through the types required to fill in functions in the `.ml` files.

Have fun and please ask a tutor for help if you have problems with any of the
above steps.

If you are not done with all the exercises by the time workshop ends, beginners
are always welcome at [OCaml Discord Beginners channel](https://discord.gg/vS5NqRZy)
for help, questions or explore what's happening in the OCaml world.

#### Using GitHub Codespaces (no local setup required)

If you have a GitHub account, you can complete the workshop entirely in the browser —
no Docker or local installation needed. 

> **IIT Madras students:** You can create a GitHub account using your smail
> (`@smail.iitm.ac.in`) address if you don't have one already.

1. Click the **Code** button at the top of this repository page.

   ![Click the Code button](.github/assets/follow_through_1.png)

2. Select the **Codespaces** tab, then click **Create codespace on main**.

<p align="center">
  <img src=".github/assets/follow_through_2.png" width="60%">
</p>

3. VS Code will launch in your browser with the full toolkit already installed —
   you can dive straight into the exercises.

> **Note:** GitHub Free accounts include 60 core-hours of Codespaces.
> The workshop should fit comfortably within this limit.


#### Useful Links:
- [Library
  documentation](https://ocaml.janestreet.com/ocaml-core/v0.12/doc/base/Base/index.html)
- [Links to other tutorials](https://ocaml.org/docs)
- [Dune - a tool for building OCaml programs](https://dune.build/)
- [A general overview of OCaml](https://ocaml.org/about)
- [The OCaml community](https://ocaml.org/community)


