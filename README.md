# ssh-repo

# ssh systems working fine setup went okay

Setting up ssh 

run the ssh tool

 $ ssh-keygen -t rsa

start the ssh agent and add the keys to the agent  

$ eval "$(ssh-agent -s)"

and add to the agent  

$ ssh-add ~/.ssh/id_ed25519

Lastly test the keys if the work 

$ ssh -T git@github.com
