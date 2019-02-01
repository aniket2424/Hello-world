# Hello-world
This is my first repository...
--------------------------------
Hi,
i am Aniket.
i  like Git-hub. it is  very user friendly...

Now going back to “git bash”; Use the command cd git to go to the git folder; now write the following commands to connect to your GitHub (enter the username and password of your GitHub when it asks you)

git config --global user.name "Your Name"
And then: git config --global user.email youremail@domain.com . Next type: git clone (url), instead of the (url), type the address of the GitHub repository that you copied from your GitHub page; (e.g. git clone https://github.com/isalirezag/Test.git).

Now if you do ls command you will see your repository there; If you also open the git folder that you have in your window you will see that your repository is added as a folder.

Now use the cd command to go to the repository: cd Test

Go ahead and copy and paste any files that you want to put in this repository in that folder.

In order to transfer the files to your repository you need to do following now:

Type git

add filename (filename is the file name that you want to upload) or you can type the command below if you want to add all the files in the folder:

git add .

Then type: git commit -m "adding files" . And then: git push -u origin master .

And then you should be all set, if you refresh your GitHub account the files should be there :)
