### @JW
*common repository for development*

---

#### Init submodule

`git submodule add https://github.com/<USERNAME>/<REPONAME>.git`

#### Cloning a Project with Submodules

`git clone --recurse-submodules`

If you already cloned the project and forgot --recurse-submodules, you can combine the git submodule init and git submodule update steps by running git submodule update --init. To also initialize, fetch and checkout any nested submodules, you can use the foolproof git submodule update --init --recursive.

#### Update submodules

`git submodule update --remote`

