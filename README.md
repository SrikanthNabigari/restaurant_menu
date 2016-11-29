
# Item Catalog Project for Udacity Nanodegree Program
## This is a Restaurant Menu Web Application

## To run locally(make sure you expert of theese)
- You need to run this application in virtual machine.
- Download and install Vagrant application [here](https://www.vagrantup.com/).
- You also need [Virtual Box](https://www.virtualbox.org/).
- Clone this repository using git shell.
- Change your directory to cloned repository.
- Now type below commands in your shell.
```bash
$vagrant up
```
```bash
$vagrant ssh
```


## To initialze the project run the following commands

Create user catalog for Posgresql db

```
sudo su - postgresql
```

```
psql
CREATE USER catalog WITH PASSWORD 'xxx';
CREATE DATABASE restaurantmenuwithusers;
\q 
```

```bash
$python database_setup.py 
```
```bash
$python lotsofmenus.py
```
```bash
$python project.py
```

Now open http://localhost:5000 in your browser.


