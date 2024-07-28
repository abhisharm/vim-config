This is a repository to help set up new vim environments.

It will use the submodule functionality of git along with vim's native package
management system to install all necessary packages.

When installing a vim plugin, you can add it as a submodule as a script:

git submodule add $repo pack/plugins/$start\_opt/$package\_name (pretty much the same thing you do when you run git clone)

git submodule update --remote --merge
