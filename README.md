# git submodule

1. `git submodule add [-b BRANCH] <REPOSITORY> [<PATH>]`
2. add `include 'PATH'` in settings.gradle
4. add `implementation project(':PATH')` in build.gradle dependencies
4. `git submodule init`

### For Example

REPOSITORY : https://github.com/Aery9527/misty-utils.git

PATH : misty-utils

1. git submodule add https://github.com/Aery9527/misty-utils.git \
   or \
   git submodule add https://github.com/Aery9527/misty-utils.git misty-utils \
   or \
   git submodule add -b develop https://github.com/Aery9527/misty-utils.git misty-utils
2. `git submodule init`
3. `git submodule update --init --recursive`
4. add `include 'misty-utils'` in settings.gradle
5. add `implementation project(':misty-utils')` in build.gradle dependencies

---
