# termux Setup file
Basic termux setup
```
import os
os.system("apt install neofetch -y ")
os.system("apt install fish -y ")
os.system("clear")
os.system("echo [+]setup completed")
file = open("update","w")
file.write("apt update && apt upgrade -y")
file.close()
os.system("mv update /data/data/com.termux/files/usr/bin")
os.system("chmod +x  /data/data/com.termux/files/usr/bin/update")
os.system("neofetch")
os.system("python3")
```
