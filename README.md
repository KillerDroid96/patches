Working with patches:
* git format-patch -1 sha
* git format-patch -7
* git format-patch -10 HEAD --stdout > 0001-last-10-commits.patch
* cat new-feature.patch | git am
* git apply --stat blah.patch
* git apply --check blah.patch
* git am --signoff < blah.patch
