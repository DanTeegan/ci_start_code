#TESTING JENKINS!!!!!!!!



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
- inside the .ssh file i pasted the following code: ```ssh-keygen -t rsa -b 4096 -C "YOURGITHUBEMAIL@EMAIL.COM"```
- CAT displayed the key using its filename.pub
- Copyed the key generated
- Went to my github repo and clicked on settings
- Clicked on deploy keys
- Pasted the key into the repo

## It is essential and best practise to write descriptive names for example daniel-jenkins
- Now the secured public key from our local system has been copied to our cloud/Github

## Private access key
- This is essentially the same as using a padlock. So when accessing 

##  Jenkins is an automation tool programmed in java
- We can use Jenkins to automate any tests we need to run.
- Using the private access key

## Differance between CI and CD

SOURCE --> BUILD --> TEST       PRODUCTION
CI --------------------->       CD ------->

Delivery is after the tests, we do the delivery manually

Simply put, CI is the process of integrating code into a mainline code base. ... CD is about the processes that have to happen after code is integrated for app changes to be delivered to users. Those processes involving testing, staging and deploying code.

