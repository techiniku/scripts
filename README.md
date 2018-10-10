# Scripts
POSIX compatible scripts to make tasks easier. Tested on macOS and Debian Linux.

## Backups
Really basic for now. Backs up to $HOME/backups/ by default. Edit variables at the top of the script for your specific environment.

* wpdb &mdash; WordPress Database Backup, mysqldump with --add-drop-table, backs up a database with the same name as the user by default
* wpfb &mdash; WordPress File Backup, tars a folder named www in the user&rsquo;s home directory by default, easily configure files to exclude

## Planned Features
* Eventually there will be a config file, or maybe the scripts should pick up variables from your environment instead
* Help text