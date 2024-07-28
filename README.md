# ansible_restore
Restore my Laptop with restic

Simple playbook that expects a Thumb drive labeled BACKUP_HOME with a restic repo on it, be mounte at /media/$USER/BACKUP_HOME

* It ask for the restic repo password
* Shows you the snapshots in the repo
* Asks for the snaphost ID you want to restore
* Restores the files listet in the restic_include file


