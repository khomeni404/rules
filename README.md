# rules

1. Make sure that Git GUI and Bash installed
2. Go a project directory from WE
3. right click and open Git Bash
    cmd: git init
    cmd: git add -all
    cmd: git commit -m "Initial Commit"
4. Close Bash and Open Git GUI
   press push, a box will appeare with locate master repo as source branchase
   paste url into "Arbitary Loacation". ie: https://github.com/khomeni404/mix.git



===============================================
sadat@DESKTOP-BU6AKN4 MINGW64 /e/Project
$ ssh-keygen -t rsa -b 4096 -C "khomeni404@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/sadat/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):    ###### like.. abc, cook
Enter same passphrase again:
Your identification has been saved in /c/Users/sadat/.ssh/id_rsa.
Your public key has been saved in /c/Users/sadat/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:DMx0cVRzZtnfVx8N/UPLdIpZQObEzv/aC5qEtDj4xmQ khomeni404@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|      . ooo+B.==.|
|     + . . +.=o+*|
|      +    o.++.X|
|       o    = .+*|
|        S.   .  o|
|      .Eo o   .  |
|     .+o o . . . |
|      .o. . o ...|
|      ..   o  .oo|
+----[SHA256]-----+

sadat@DESKTOP-BU6AKN4 MINGW64 /e/Project
$ eval $(ssh-agent -s)
Agent pid 245

sadat@DESKTOP-BU6AKN4 MINGW64 /e/Project
$ ssh-add ~/.ssh/id_rsa
Enter passphrase for /c/Users/sadat/.ssh/id_rsa:
Identity added: /c/Users/sadat/.ssh/id_rsa (khomeni404@gmail.com)

sadat@DESKTOP-BU6AKN4 MINGW64 /e/Project
$ clip < ~/.ssh/id_rsa.pub    ###### to copy key

#Save key in github > Setting > SSH Key

sadat@DESKTOP-BU6AKN4 MINGW64 /e/Project
$ git clone git@github.com:khomeni404/isCool.git
