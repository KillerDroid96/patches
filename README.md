Working with patches:
gcp -m 1 
git format-patch -1
git format-patch -10 HEAD --stdout > 0001-last-10-commits.patch
cat new-feature.patch | git am
git am < file.patch
git apply --stat blah.patch
git apply --check blah.patch
git am --signoff < blah.patch
