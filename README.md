# git submodule

1. `git submodule add [-b BRANCH] <REPOSITORY> [<PATH>]`
2. `git submodule init`
3. `git submodule update --init --recursive`
4. add `include 'PATH'` into settings.gradle
5. add `implementation project(':PATH')` into build.gradle dependencies

### For Example

REPOSITORY : https://github.com/Aery9527/misty-utils.git

PATH : misty-utils

1. `git submodule add https://github.com/Aery9527/misty-utils.git` or\
   `git submodule add https://github.com/Aery9527/misty-utils.git misty-utils` or\
   `git submodule add -b develop https://github.com/Aery9527/misty-utils.git misty-utils`
2. `git submodule init`
3. `git submodule update --init --recursive`
4. add `include 'misty-utils'` in settings.gradle
5. add `implementation project(':misty-utils')` in build.gradle dependencies

---
