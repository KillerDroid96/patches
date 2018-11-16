Working with patches:
* git format-patch -1 sha
* git format-patch -7
* git format-patch -10 HEAD --stdout > 0001-last-10-commits.patch
* cat new-feature.patch | git am
* git am < file.patch
* git apply --stat blah.patch
* git apply --check blah.patch
<<<<<<< HEAD
* git am --signoff < blah.patch
=======
* git am --signoff < blah.patch
>>>>>>> 7de27d43e54abd684cb52a42035de1d10af075af
