# neovim-distros

Compile a neovim branch for different distros and install locally in bob.
To make the newly compiled nvim accessible by bob, you have to add a symlink with the correct version numbering for bob, e.g.:
'''
lrwxrwxrwx 1 nobody nobody 11 Jun 14 11:29 v0.10.1 -> v0.10.1-dev
drwxrwxr-x 3 nobody nobody 4096 Jun 14 11:27 v0.10.1-dev
'''
after that execute `bob list` to ensure the correct version and then `bob use <version>`.
