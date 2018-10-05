# git-lfs-diff

As git-lfs is primarily intended for storing binary files, it does not support the diff operation. However, for cases when git-lfs is being used for large text files, a diff operation would be useful...

This script performs a diff operation between 2 specified revisions of a file stored in git-lfs.

This script originates from the comment made by Taylor Blau in:
https://github.com/git-lfs/git-lfs/issues/2498
