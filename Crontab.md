# Crontab

![image](https://github.com/Banzly/RHCSA-Linux-9-Notes/assets/113104087/65ff68a1-f065-440f-a399-dbc1b8d75762)


``crontab -e``
Edits the current crontab using the editor specified by the VISUAL or EDITOR environment variables.


## Anacron



## At

The **atd** service needs to be running to run one-time only jobs.

``at 11:25AM`` to schedule job.
You enter an interactive shell and you use Ctrl-D to close it.

Use ``at -l`` to list all pending jobs.
To see the contents of a scheduled job. ``at -c [job_number]``
Use ``atrm`` to remove jobs from the list.
