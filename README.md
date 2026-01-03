# Burpsuite Pro Installation Guide (Cracked)

At first download the burpsuite pro jar file

**Download Link:** [https://portswigger.net/burp/documentation/desktop/getting-started/download-and-install](https://portswigger.net/burp/documentation/desktop/getting-started/download-and-install)

![1767440123020](image/README/1767440123020.png)


**Download the jar file**

![1767440157724](image/README/1767440157724.png)

Move downloaded files to /opt/burpsuitepro

```
# Let's create folder
sudo mkdir /opt/burpsuitepro

# Go to your files location

cd /locationofpng,loader,jar

# Move all files (loader, png, burpsuite jar) to /opt/burpsuitepro/

mv * /opt/butpsuitepro
```


```

# Create Necessary folders and file

mkdir -p ~/.local/share/applications
nano ~/.local/share/applications/burpsuitepro.desktop

# Paste this in .desktop file

[Desktop Entry]
Name=Burp Suite Professional
Comment=Web security testing platform
Exec=java -jar /opt/burpsuitepro/loader.jar
Icon=/opt/burpsuitepro/burp_suite.ico
Terminal=false
Type=Application
Categories=Development;Security;WebDevelopment;
StartupWMClass=burpsuite

# Give executable permission and create a soft link to launch with terminal

chmod +x ~/.local/share/applications/burpsuitepro.desktop
update-desktop-database ~/.local/share/applications/
sudo ln -s /opt/burpsuitepro/loader.jar /usr/local/bin/burpsuitepro

# Type this command to launch the burpsuite pro, Not now because we didn't cracked the burpsuite pro yet

burpsuitepro


# Go to the location

cd /opt/burpsuitepro/

# Run the loader

java -jar loader.jar
```

**Change it to your name**

![1767436999088](image/index/1767436999088.png)

Copy this licence texts

![1767437038207](image/index/1767437038207.png)

Now click the run

![1767437063532](image/index/1767437063532.png)

Paste here and next

![1767437113114](image/index/1767437113114.png)

Click Manual Activation

![1767437142361](image/index/1767437142361.png)

Copy request code

![1767437172232](image/index/1767437172232.png)

Paste here and copy the response

![1767437212198](image/index/1767437212198.png)

Paste here

![1767437237993](image/index/1767437237993.png)

**Congrates! You did it**

![1767437263466](image/index/1767437263466.png)

Now copy this command from the loader

![1767437300197](image/index/1767437300197.png)

Edit launcher and replace the launching command

![1767437408704](image/index/1767437408704.png)

For Debian Edit this

```
[Desktop Entry]
Name=Burp Suite Professional
Comment=Web security testing platform
Exec=java -jar /opt/burpsuitepro/loader.jar
Icon=/opt/burpsuitepro/burp_suite.ico
Terminal=false
Type=Application
Categories=Development;Security;WebDevelopment;
StartupWMClass=burpsuite
```

Change this executable command

![1767437616331](image/index/1767437616331.png)

Now all jobs done

![1767437459832](image/index/1767437459832.png)
