##  Configure to mysql workbench host server
First of all download to MysqlWorkbench
```
sudo apt update
```
```
sudo apt install mysql-workbench -y 
```
# Go to the show application in your system 


<img src="1.png" alt="drawing" width="500"/>

# Type to mysql workbench
 

<img src="2.png" alt="drawing" width="500"/>


# Open mysql workbench 


<img src="3.png" alt="drawing" width="500"/>

## And click to add conection

<img src="4.png" alt="drawing" width="500"/>

## Type yor name project 


<img src="5.png" alt="drawing" width="500"/>


<img src="6.png" alt="drawing" width="500"/>

## Then click to connection method and click to standerd tcp/ip over ssh

```
now add your host name =  your ip 

ssh user = name your machine name 

then click to ssh key file 
```

## Go to your .ssh file and add your key 

<img src="7.png" alt="drawing" width="500"/>

```
home > presh key ctrl+h >find .ssh > select key id_rsa
```

Now add host name = your host

Add user name = your db user

# Then click to 
```
password :  store in keychain pest your db password
```


# Now click to test conection
