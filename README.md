opentxs-server
==============

[![Build Status](https://travis-ci.org/Open-Transactions/opentxs-server.svg?branch=develop)](https://travis-ci.org/Open-Transactions/opentxs-server)[![Stories in Ready](https://badge.waffle.io/open-transactions/opentxs-server.svg?label=ready&title=Ready)](http://waffle.io/open-transactions/opentxs-server)


### Contributing

If you are planning to contribute please contact the devs in #opentransactions @ freenode.net IRC chat.

All development goes in develop branch - please don't submit pull requests to master.

Please do *NOT* use an editor that automatically reformats.

As part of our [Continuous Integration system](https://travis-ci.org/Open-Transactions/opentxs)
we run [cppcheck](https://github.com/danmar/cppcheck/) and 
[clang-format](http://clang.llvm.org/docs/ClangFormat.html). The build will fail
if either of them finds problems.

#### CppCheck and clang-format Git hooks

For convenience please enable the git hooks which will trigger cppcheck and
clang-format each time you push or commit. To do so type in the repo directory:

    cd .git/hooks  
    ln -s ../../scripts/git_hooks/pre-push
    ln -s ../../scripts/git_hooks/pre-commit
 
To check your code without pushing the following command can be used:  

    git push -n


### Dependencies

[Open Transactions library](https://github.com/Open-Transactions/opentxs)
