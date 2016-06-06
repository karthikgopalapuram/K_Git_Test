## Git Commands for Version Control

##### Creating a repository online for the <b>first time</b>
``` sh
$ git init
$ git add README.md
$ git commit
```
On mac this will take you to the default editor(Vi) to escape that you need to do the following : 
+ Press *Esc*
+ Enter *:wq*

But you can also use the nano editor for editing text files. The syntax will be as follows :
``` sh
$ nano <your file>
```
You can then write the changes to file and save it using the follwoing commands on mac
```sh
Control + O  # to write the changes to the file and save
Control + X  # exit the editor
```

``` sh
$ git commit -m "First Commit"  # commits everything in staging to be ready to be pushed to Githib
$ git remote add origin https://github.com/karthikgopalapuram/K_Git_Test.git
$ git push -u origin master
# put in your **username** and **password**
```

##### When you want to add on to repository online with changes
``` sh
$ git add .
$ git add -u # when you deleted a local file you want to remove it from your repo
$ git commit -m "What has changed"
$ git push
# put in your **username** and **password**
```

* . means add all the files included in the folder.


##### No more username and password input for every push
``` sh
$ git remote set-url origin git@github.com:karthikgopalapuram/K_Git_Test.git
```
