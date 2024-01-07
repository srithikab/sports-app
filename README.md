# sports-app

## One time SSH key setup on Laptop
### Generate an SSH Key Pair
Open a new Terminal window
Type ssh-keygen -t rsa 
You will be prompted to enter a filename. By default, your keys will be saved as id_rsa and id_rsa.pub. Simply press Enter to confirm the default - there is no need to change this unless you have multiple keys! (Note: if you would like to change the default filename, you'll need to include the complete file path)
When prompted, enter a passphrase.
This will create a hidden directory called .ssh that contains both your public (id_rsa.pub) and private (id_rsa.) key files.

### Copy Key to git repo

## Opening a Sports App in Android Studio
To open one of the Sports App in Android Studio, begin by checking out the branche from git repo, and then open the root directory in Android Studio. The following series of steps illustrate how to open the Sports App.

Clone the repository:
```
git clone git@github.com:srithikab/sports-app.git
```

Finally open the sports-app/ directory in Android Studio.
