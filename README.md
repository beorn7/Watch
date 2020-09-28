Watch
=====

Usage: ``Watch [-v] [-t]  [-p <path>] [-x <regexp>] <command>``

Watches for changes in a directory tree, and runs a command when something
changed. Note that only changes that happen while Watch is running are
detected. Also, a failed execution of the command is not retried.

-t deprecated, always true.

-v enables verbose debugging output

-p <path> specifies the path to watch (if it is a directory then it watches recursively)

-x <regexp> specifies a regexp used to exclude files and directories from the watcher.
