How to prepare MySQL for the Demo
============================================

## Install Tools

1. Update installation: `apt-get update`
2. Install unzip, git and wget with `apt-get install unzip git wget`


## Clone repo

3. Ensure you are in the directory: `cd ~`
4. Clone this repo: `git clone https://github.com/puckpuck/planespotter.git`
5. Change the two DB shell scripts to be executable `chmod +x ~/planespotter/db-install/*.sh`


## Create Database

6. Execute the DB creation script `~/planespotter/db-install/create-planespotter-db.sh` 

NOTE: The password that gets asked, is the MySQL Root Password.


## Cleanup

If you ever want to recreate the database, you can use the database deletion script `~/planespotter/db-install/delete-planespotter-db.sh` to drop the database, and then Create the Database again.

