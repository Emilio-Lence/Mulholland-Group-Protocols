Mulholland-Group-Protocols
==========================

This is a respository containing protocols for use of computational chemistry software used by the Mulholland research group University of Bristol.


This repository uses version control software called [git](http://git-scm.com/) and
is stored on GitHub [here](https://github.com/patrickveegee/Mulholland-Group-Protocols).  
See [here](https://github.com/swcarpentry/boot-camps/blob/2013-09-bristol/version-control/README.md) for an introduction to version control using git.  

The task of populating this repository will be divided up in this [to do list](to_do_list.md)

Text files in this repository are written in markdown which you can learn the basics of in a couple of minutes [here](http://www.markdowntutorial.com/).

###View and edit this repository on the GitHub web interface 


In your web browser navigate to the [repository web page](https://github.com/patrickveegee/Mulholland-Group-Protocols).  
To edit a file, navigate to the file then click "edit".  Once you have changed the file scroll down and enter a comment in the "commit summary"
box, then hit the green "Commit Changes" button.  
To add new files click on the + symbol that appears after the current directory path

###Download and edit this repository on Mac or UNIX (e.g. one of the chemistry clusters curie or grendel): 

First ensure that git is installed. Instructions are [here](http://git-scm.com/downloads)  
Git is installed on curie: /users/pv7409/bin/git and on bluecrystal /usr/local/bin/git
Make sure these installations are in your [path](http://www.cyberciti.biz/faq/unix-linux-adding-path/)

Command-line:

1) Open your internet browser and visit https://github.com/patrickveegee/Mulholland-Group-Protocols

2) In the bottom right-hand corner there is a title saying "HTTPS clone URL" and a url in a field below it : "https://github.com/patrickveegee/Mulholland-Group-Protocols.git"
Copy this link 

3) Go to your command line and cd to a suitable location to create the Repository
Then type 
$ git clone https://github.com/patrickveegee/Mulholland-Group-Protocols.git

4) This will download the Repository Mulholland-Group-Protocols for use on your local computer 


On Windows: 
=========== 

Mvdk 



Editing, Adding, Commiting changes made to the Mulholland-Group-Repository
--------------------------------------------------------------------------

You have made some changes to the repository and now want to save them and 'push' these changes up to the master copy that lives on the online repository Github 

1) $ git status 
Tells you what changes you have made since your last commit

2) $ git add --all 
Initializes all the changes that you have made (detailed in the previous command)
alternatively, 
$ git add README.md    
would only add the changes made to the file README.md 

3) $ git commit 
This then saves the changes that you have just added. It will require you to write a message giving the details of this specific git so that other users will be able to track your changes

4) $ git push 

Pushes your changes up to Github (online repository). This will require you to enter your individual username and password.
Your changes will now be visible to all the subscribers of the repository online. 
NOTE
If when you push you receive the following message:

"To https://limbma@bitbucket.org/peeveegee/mulholland-group-protocols.git

 ! [rejected]        master -> master (non-fast-forward)

error: failed to push some refs to 'https://limbma@bitbucket.org/peeveegee/mulholland-group-protocols.git'

hint: Updates were rejected because the tip of your current branch is behind

hint: its remote counterpart. Merge the remote changes (e.g. 'git pull')

hint: before pushing again.

hint: See the 'Note about fast-forwards' in 'git push --help' for details. 
" 

This means some changes have been made the repository since you last "pulled" it from Github 
Therefore you need to

$ git pull 

To update the repository you are working on (which requires another you to write a message to let other username know the details of this action)
and then you will be able to do 
$ git push 

to make your changes 


