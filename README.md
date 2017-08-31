# kernel

Forked version of kernel with ClearOS changes applied

* git clone git+ssh://git@github.com/clearos/kernel.git
* cd kernel
* git checkout c7
* git remote add upstream git://git.centos.org/rpms/kernel.git
* git pull upstream c7
* git checkout clear7
* git merge --no-commit c7
* git commit

To fetch sources:

* ln -sf ../common/Makefile
* make srpm
