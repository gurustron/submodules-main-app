# Submodules: Main app

Main app which will consume submodules
[Git Tools - Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)


## Steps Done

- [x] Add submodule
  `git submodule add https://github.com/gurustron/submodules-first-library ./submodules/FirstLibrary`
- [x] Check out project with submodules (other machine/folder)
  1. [x] Multistep:
     1. ```bash 
        git clone git@github.com:gurustron/submodules-main-app.git
        ```
     2. ```bash
        git submodule init
        ```
     3. ```bash
        git submodule update
        ```
  2. [x] Single step:
     ```bash
     git clone --recurse-submodules git@github.com:gurustron/submodules-main-app.git
     ```
  3. [ ] Rider UI
- [ ] Update from remote  
  Branch is "fixed" until the submodule remote is updated and pushed to the repo containing the submodule. So no changes are shown in new checkouts/updated of the Main app until then. 
  1. [x] Rider UI 
  2. [ ] Terminal commands
     1. [x] From submodule directory:
        1. ```bash
           git fetch
           ```
        2. ```bash
           git merge origin/main
           ```
     2. [ ] From root
   
