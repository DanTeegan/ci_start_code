# Why should we use SSH with Github

## SSH Keys and github
## There are two methods to clone the repo

    SSH AND HTTPS
   -We have two types of repos ```Public repo```
   - Second is ```Private repo```

YOUR LAPTOP - SECURED

CI-START-CODE
PUBLIC - NOT SECURED

CI-START-CODE
PRIVATE-SECURED

- Generate SSH keys on your local system
- Copy the key from local system to the specific repo on git-hub (ci-start-code)
- ssh folder where the ssh keys are available
- name the new key as my name "Daniel"
- inside the .ssh file i pasted the following code: ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
- CAT displayed the key using its filename.pub
- Copyed the key generated
- Went to my github repo and clicked on settings
- Clicked on deploy keys
- Pasted the key into the repo

# It is essential and best practise to write descriptive names for example daniel-jenkins
- Now the secured public key from our local system has been copied to our cloud/Github
