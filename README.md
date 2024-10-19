# SSH-Key



```bash
ssh-keygen -t rsa -b 4096 -C "github" && cat ~/.ssh/id_rsa.pub


## seconde way

ssh-keygen -t rsa -b 4096 -C "your_email@example.com"


cat ~/.ssh/id_rsa.pub



git remote set-url origin git@github.com:Kewmarse/app.git

# verify the change
git remote -v




git push -u origin master

