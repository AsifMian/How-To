## Installing Webmin (A Graphical user interface ) for EC2 Ubuntu server

### Step 1: Update the Ubuntu System
```
sudo apt update
```
## Then 

```
sudo apt install wget apt-transport-https software-properties-common
```

### Step 2: Import Webmin Repository Key

```

wget -q -O- http://www.webmin.com/jcameron-key.asc | sudo apt-key add -

```

Update Webmin repository to the sources by running the following command, the command will append the Webmin repository link at the bottom of the file and update the system package lists.

```

sudo add-apt-repository "deb [arch=amd64] http://download.webmin.com/download/repository sarge contrib"

```

### Step 3: Install Webmin on Ubuntu (AWS EC2 Instance)

```

sudo apt install webmin

```

### Step 4: Configure AWS EC2 Ubuntu instance to disable SSL (optional i recommed not to perform this step)

```
sudo vim /etc/webmin/miniserv.conf

```

And change ssl=1 to ssl=0 on the /etc/webmin/miniserv.conf. 

### Step 5: Configure password
we need to configure passwords for Webmin users to access the dashboard. 
```

sudo vim /usr/share/webmin/changepass.pl /etc/webmin root “YOUR STRONG PASSWORD”

```

### Step 6: Access Webmin via port 10000
if you disabled ssl use http instead of https

```

https://your-ip:10000

```


