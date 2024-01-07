# sports-app

## One time SSH key setup 
### Generate an SSH Key Pair on Laptop
1. Open a new Terminal window
2. Type ssh-keygen -t rsa 
3. You will be prompted to enter a filename. By default, your keys will be saved as id_rsa and id_rsa.pub. Simply press Enter to confirm the default - there is no need to change this unless you have multiple keys! (Note: if you would like to change the default filename, you'll need to include the complete file path)
4. When prompted, don't enter passphrase and press enter
5. This will create a hidden directory called .ssh that contains both your public (id_rsa.pub) and private (id_rsa.) key files.

### Copy Key to git repo 
  1.  Copy the public key by following the steps
  2.  cat ~/.ssh/id_rsa.pub
  3.  Copy the ssh-rsa
  4.  Go to 	https://github.com/srithikab/sports-app/settings/keys
  5.  Click on deploy key button and Paste the ssh-rsa key and click on add key


## Opening a Sports App in Android Studio
To open one of the Sports App in Android Studio, begin by checking out the branche from git repo, and then open the root directory in Android Studio. The following series of steps illustrate how to open the Sports App.

Clone the repository:
```
git clone git@github.com:srithikab/sports-app.git
```

Finally open the sports-app/ directory in Android Studio.
