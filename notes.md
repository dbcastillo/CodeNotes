How to setup bash on Windows
- install ubuntu from the microsoft store
- search control panel and go to programs
- hover over programs and features
- click on turn windows feaures on or off 
- scroll down to Windows subsystem for Linux and tick it and click ok 
- reboot 
- once reboot is complete, login and open the command prompt and type bash and hit enter
- reference: https://bayton.org/docs/linux/ubuntu/install-bash-on-windows-10-build-14316/

Download vs code for Windows
- https://code.visualstudio.com/download

SSH Key generation for Windows (necessary if pushing for first time on new machine...i think...pretty sure!)
- https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
- view SSH key with command <cat ~/.ssh/id_rsa.pub>
- copy from Windows bash using command <Ctrl + Shift + C>
- password authentication was removed in 2021, they require personal access token instead
- https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token

How to delete a git branch
- Github: make sure you're on the branch, run command "git push origin --delete <branch-name>"
- Locally: make sure you're not on the branch, run command "git branch -D <branch-name>"
