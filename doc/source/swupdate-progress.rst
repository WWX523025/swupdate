progress
========

progress that tries to connect to a running instance
of SWUpdate to get the status of a running update.

SYNOPYS
-------

swupdate-progress [option]

DESCRIPTION
-----------

swupdate-progress is an example how to connect to SWUpdate via the progress interface.
It shows on the stdout a simple bar with the procent indication of the current update
and reports the result of the update. It can optionally drive "psplash" or execute a script
after an update.

-c
        Use colors to show results on stdout
-e
        Command to be execute after an update
-p
        send percentage to psplash
-r
        optionally reboot the target after a successful update
-s
        path to progress IPC socket in case the default is not taken
-w
        waits for a SWUpdate connection instead of exit with error
-h
        print a help
        
