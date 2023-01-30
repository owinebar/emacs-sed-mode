# emacs-sed-mode

obs-service-sed is useful because sed is restricted in how it interacts with the host system.
However, editor support for writing complex sed programs is limited.  AFAIK, emacs's sed-mode is it.
However, that support is still limited - e.g. it does not support extended regular expression syntax.
It does not support the GNU extensions to the a,i, and c commands to use the text following whitespace
on the same line.

So this repo is for my enhancements to sed-mode, whenever I get around to them.  As the author
of sed-mode notes, needing to use sed-mode indicates possible derangement.
Except for applications like obs-service-sed.
