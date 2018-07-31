See https://micooke.github.io/

*** To add a new submodule
git submodule add https://github.com/user/repo repo
git submodule update --init --recursive
git commit -m "add submodule : user/repo"

*** To sync a submodule
git submodule update --remote --merge

From : https://gist.github.com/myusuf3/7f645819ded92bda6677
To remove a submodule you need to:
1. Delete the relevant section from the .gitmodules file.
2. Stage the .gitmodules changes git add .gitmodules
3. Delete the relevant section from .git/config.
4. Run git rm --cached path_to_submodule (no trailing slash).
5. Run rm -rf .git/modules/path_to_submodule (no trailing slash).
6. Commit git commit -m "Removed submodule "
7. Delete the now untracked submodule files rm -rf path_to_submodule


