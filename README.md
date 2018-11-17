| Command | Description | 
| --- | --- |
| git format-patch -1 SHA | Creates .patch for 1 specific commit |
| git format-patch -7 | Creates 7 .patches from last 7 commits |
| git format-patch -10 HEAD --stdout > last-10.patch | Creates .patch with last 10 commits combined |
| git apply --stat blah.patch | Status of .patch |
| git apply --check blah.patch | Checks .patch for errors |
| git am --signoff < blah.patch | Applies the .patch | 
