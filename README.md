# cust-nvim (LAZYVIM)
## FIRST INSTALL NEOVIM (in ubuntu)
- [Download nvim.appimage](https://github.com/neovim/neovim/releases/download/stable/nvim.appimage) 
-  cd to the place you have downloaded the image
-  then chmod to give sudo privilege
``` sh
 chmod u+x nvim.appimage
```
``` sh
./nvim.appimage
```
- Now when you run nvim youll face an error
``` sh
bash: /usr/bin/nvim: No such file or directory
```
- To combat this , move appimage into /usr/bin/nvim
``` sh
sudo mv nvim.appimage /usr/bin/nvim
``` 

1.  Requirements ⭐
   - latest nvim >=v0.9.0
   - latest git >=2.19.0
   - gcc
   - grep and fd
```  bash
     sudo apt install ripgrep
     sudo apt install fd-find
```
  - a terminal that support true color and undercurl

2. INSTALLATION 🧑‍🏭
   - clone repo to /.config/nvim
     ``` sh
     git clone https://github.com/LazyVim/starter ~/.config/nvim
     ```
  
![image](https://github.com/KRIISHSHARMA/cust-nvim/assets/86760658/fa0c2315-d4f7-4e8c-b68b-421ef760b839)

# CHEATSHEET (space key is the leader)
- opening and closing side bar : spacekey + e
- renaming / deleting file : r/n
- navigating files : spacekey + f + f ( to escape press esc + esc ) (for more press spacekey + f to see more related commands)
- to reach top : gg
- to reach bottom : G
- to fastforward  : e
- start of line : 0
- to search a file : spacekey + s + g (or spacekey+ s to view other related commands)
- 
