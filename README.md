## Configur to mysql workbench host server
# First of all download to MysqlWorkbench
```
sudo apt update
```
```
sudo apt install mysql-workbench -y 
```
# Go to the show application in your system 

![This is an image](https://raw.githubusercontent.com/akonverma97/configure-mysqlworkbeanch/main/1.png)

# Type to mysql workbench
 
![This is an image](https://raw.githubusercontent.com/akonverma97/configure-mysqlworkbeanch/main/2.png)


# Open mysql workbench 

![This is an image](https://raw.githubusercontent.com/akonverma97/configure-mysqlworkbeanch/main/3.png)

## And click to add conection

![This is an image](https://raw.githubusercontent.com/akonverma97/configure-mysqlworkbeanch/main/4.png)

## Type yor name project 

![This is an image](https://raw.githubusercontent.com/akonverma97/configure-mysqlworkbeanch/main/5.png)

## Then click to connection method and click to standerd tcp/ip over ssh

![This is an image](https://raw.githubusercontent.com/akonverma97/configure-mysqlworkbeanch/main/6.png)


```
now add your host name =  your ip 

ssh user = name your machine name 

then click to ssh key file 
```
## Go to your .ssh file and add your key 

![This is an image](https://raw.githubusercontent.com/akonverma97/configure-mysqlworkbeanch/main/7.png)


```
home > presh key ctrl+h >find .ssh > select key id_rsa
```


## Now add host name = your host
## Add user name = your db user

## Then click to 
```
password :  store in keychain pest your db password
```

![This is an image](https://raw.githubusercontent.com/akonverma97/configure-mysqlworkbeanch/main/8.png)
## Now click to test conection
