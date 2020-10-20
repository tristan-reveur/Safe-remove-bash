# srm comand from bash

## `How to use and install?` 

### First you need copy my repository from your directory

>`cd ~ `

>`git clone https://github.com/tristan-reveur/Safe-remove-bash`

---
#### and open your bash console and enter comand:

>`cd ~/Safe-remove-bash`

>`chmod +x srm`

>`mkdir ~/bin`

>`cd ~`
---

#### Next Open your `.bash_profile`

>`nano .bash_profile`

#### Add :

>`export PATH="${PATH}:~/bin" `

Reconnect bash, try `echo $PATH` , you see `~/bin`. Enter to terminal next commands:

>`cd ~/Safe-remove-bash`

>`cp srm ~/bin/srm`

## **Done!** Now you can use the command `srm`. It will save files you delete to ***RECYCLE*** and your files delete after 7 days.
