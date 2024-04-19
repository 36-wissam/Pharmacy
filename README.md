# Pharmacy-DB

simple pharmacy management system implemented in Python.
## Requirments Installation

install  customtkinter library using the following command:

```
python[your python version] -m pip install customtkinter
```
Like:
```
python3.11 -m pip install customtkinter
```
mysql-connector library :

```
python3.11 -m pip install mysql-connector-python
```


Pillow library :

```
python3.11 -m pip install Pillow
```




## How to install Mysql on Ubuntu Linux
- Install mysql-server
``` 
sudo apt update
sudo apt install mysql-server
```
- Start mysql
```
sudo systemctl start mysql.service
```
- Run secure installation
```
sudo mysql_secure_installation
```
- Always choose to VALIDATE PASSWORD otherwise it might set password to blank and leads to unwanted problems
- Read and go through the rest of the security installation 
- Set localhost
```
sudo mysql
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password by 'the password that you set before'
```
- You can exit mysql by
```
exit
```
- Install workbench
```
sudo snap install mysql-workbench-community
```


## How to use mysql commandLine after setting a password
- Start it up
```bash
sudo mysql -r -p
```
- Enter the password