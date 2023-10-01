```
███╗   ███╗██████╗ ███████╗ ██████╗ ██╗  ██╗██╗███████╗
████╗ ████║██╔══██╗██╔════╝██╔═══██╗╚██╗██╔╝██║██╔════╝
██╔████╔██║██████╔╝█████╗  ██║   ██║ ╚███╔╝ ██║█████╗  
██║╚██╔╝██║██╔══██╗██╔══╝  ██║   ██║ ██╔██╗ ██║██╔══╝  
██║ ╚═╝ ██║██║  ██║██║     ╚██████╔╝██╔╝ ██╗██║███████╗
╚═╝     ╚═╝╚═╝  ╚═╝╚═╝      ╚═════╝ ╚═╝  ╚═╝╚═╝╚══════╝
```
# Repair Kex in Kali NetHunter Rootless 
This is for kex repair and solve all vnc server error in kalinethunter

# Installation-NetHunter
```
sudo apt update 
sudo apt install git -y # ignore if installed
# ignore upper lines if you already installed git
cd ~/
git clone https://github.com/mrfoxie/repair-kex.git
cd repair-kex
sudo chmod +x repair-kex
sudo ./repair-kex
```

# Beta Installation-NetHunter
```
# Most of NetHunter already have git pre installed if not then install it.
sudo apt update
sudo apt install git -y
cd ~/
git clone https://github.com/mrfoxie/repair-kex.git
cd repair-kex
sudo chmod +x repair-kex
sudo ./beta-repair-kex
```

# Uninstall
```
cd ~/repair-kex
chmod +x uninstall-kex
sudo ./uninstall-kex
```
