Have your repo

### Step 1
Open Terminal
cd to user folder `cd`
check where you are `pwd`

cd to .ssh folder
or make it if you don't have it
`mkdir .ssh`

cd to .ssh folder

check what's in it `ls`

generate ssh key to go straight into our .ssh folder (shouldnt be anyware else at all!)


`ssh-keygen -t rsa -b 4096 -C "emailaddress"`

will say: generating public/private rsa key pair
will ask you to enter the file you want to save the key in

enter the file name e.g "github_test_key"

no keyphrase right now, so just press enter
and enter again 

will show randomart image

Check for your key pair `ls`
Should see the same file name twice, but one with a `.pub` extension

Now we put the public key onto our repo
So we'll open the cintents of the public key
`sudo nano "key file name.pub"`
or
`cat "key file name".pub`

copy the key (ensure no whitespaces)

### Step 3
Adding the public key to our repo
Go to Github
Go to settings
Go to deploy keys
click `add deploy key`
Add good title
inside "key" paste your key
click `allow write access`
click `add key`


### Step 4
Back to the repo on your local machine
delete the repo
check if it's there `ls`
try to clone it with ssh
-back to Github
-copy the ssh key link
back to pycharm
`git clone "ssh link"`
shouldn't work!! It doesnt know which ssh key it needs to be using
- could do it in the .ssh folder - DO NOT!!!


### Step 5
Creating a process to store the ssh key we want to use (acts like a keyring)
Open a second Terminal window
navigate to where you want to clone the repo
`cd "folder path"` 

```
eval `sss-agent` 
```
Should return `Agent pid "number"`

Add the path to the ssh key
`ssh-add ~/.ssh/"key file name"`
Should return `Identity added: (etc)` (with email you input earlier at the end)
(The path & the comment you added)

Test the connection to the ssh
`ssh -T git@github.com`
Should return `Hi "username" You've successfully created (etc)`

Now we actually clone the repo
Back to Github
Copy ssh key link
-Back to terminal above
`git clone "ssh link"`

check `ls`

