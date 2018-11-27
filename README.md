# vagrant_c

### Purpose of the repository 
- The repository uses nginx64 and mysql64 boxes already uploaded in `vagrant` cloud and sets mutlti-machines to web01, web02 and mysql.

#### List of files in the repository

File name                            | File description 
------------------------------------ | --------------------------------------------------------------
`Vagrantfile` | file with script that defines machine and software requirements and sets mutlti-machine web01, web02 and mysql.


### How to use this repository. 
- Install `virtualbox` by following this [instructions](https://www.virtualbox.org/wiki/Downloads).
- Install `vagrant` by following this [instructions](https://www.vagrantup.com/docs/installation/).
- Clone the repository to your local computer: `git clone git@github.com:nikcbg/vagrant_c.git`.
- Go to the cloned repo on your computer: `cd vagrant_c`.
- After that execute the commands in the table below.

Command execution                    | Command outcome
------------------------------------ | --------------------------------------------------------------
`vagrant up` | to power up the nginx64 VM.
`vagrant ssh` | to log in to the nginx64 VM.


### TO DO:
- Check if `web01`, `web02` and `mysql` are created and have the neccesery code installed. 
