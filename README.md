## Git Commands for Version Control

##### Creating a repository online for the <b>first time</b>
```
$ git init
$ git add README.md
$ git commit
```
On mac this will take you to the default editor(Vi) to escape that you need to do the following : 
+ Press *Esc*
+ Enter *:wq*
```
$ git commit -m "First Commit"
$ git remote add origin https://github.com/karthikgopalapuram/K_Git_Test.git
$ git push -u origin master
# put in your **username** and **password**
```

##### When you want to add on to repository online with changes
```
$ git add .
$ git commit -m "What has changed"
$ git push
# put in your **username** and **password**
```

* . means add all the files included in the folder.