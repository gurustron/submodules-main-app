# Submodules: Main app

Main app which will consume submodules
[Git Tools - Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)


## Steps Done

- [x] Add submodule
  `git submodule add https://github.com/gurustron/submodules-first-library ./submodules/FirstLibrary`
- [x] Check out project with submodules (other machine/folder)
  1. Multistep:
     1. ```bash 
        git clone git@github.com:gurustron/submodules-main-app.git
        ```
     2. ```bash
        git submodule init
        ```
     3. ```bash
        git submodule update
        ```
  2. Single step:
     ```bash
     git clone --recurse-submodules git@github.com:gurustron/submodules-main-app.git
     ```
