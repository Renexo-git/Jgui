# Jgui

## **INSTALL**

Requirement: **GJS**

### _LINUX_

_debian@debian:~$_ **su**

_root@debian:~#_ **apt install gjs**

Download - [Jgui-master.zip](https://github.com/Renexo-git/Jgui/archive/refs/heads/master.zip)

---
### Demo application

---

### SERVER

Leave the folder files: **Jgui-master/demo/server/** on a web server. (Apache, Lighttpd, Nginx...)

You can run the built-in PHP or Python server to serve the files with the following command:

_debian@debian:~$_ **cd Jgui-master/demo/server**

**PHP**

_debian@debian:~/Jgui-master/demo/server$_ **php -S localhost:8000**

**Python**

_debian@debian:~/Jgui-master/demo/server$_ **python -m SimpleHTTPServer 8000**

**Python3**

_debian@debian:~/Jgui-master/demo/server$_ **python3 -m http.server 8000**

---

### CLIENT

_debian@debian:~$_ **cd Jgui-master/demo/client**

_debian@debian:~/Jgui-master/demo/client$_ **gjs Piano.js**

---

![ScreenShot](https://raw.githubusercontent.com/Renexo-git/Jgui/main/screenshot.png)
