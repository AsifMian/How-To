How to upload project to gitHub

type:

-1.git init
-2.git add .
-3.git commit -m "Message to Display i.e first time you time write initial comment"

**Now your Project have been Added to local machine git**

>>To push to whole project to github repository

-4.git remote add origin <repository Address> !
  i.e git remote add origin https://github.com/AsifMian/nw.git

-5.git push -u origin master

**Now Your project have been Added to gitHub**



# How to Modifiy and  save changes to github repository After

After changing the files 

if you changed the files online then 
{
  better to pull the project

  -git pull 
 
  or 
  git clone <repository address>

}

# Run:

1.git add .

For evey change you have to commit the change

2.git commit -m "New change"

check wheather all changes have been commited

3.git status

Then run

4.git push origin master

**Your changes have been saved to git repository**



How to delete branch 
>> git branch -D branchName
>> git branch -d branchName
   
 OR

>>git push origin --delete branchName

