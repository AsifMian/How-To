# How to upload project to gitHub

Type:

- 1. **git init**
- 2. **git add .**  (. to add all files otherwise you can write only one file name)
- 3. **git commit -m "Message to Display i.e first time you time write initial comment"**

**Now your Project have been Added to local machine git**

>>To push to whole project to github repository

- 4. **git remote add origin repository-Address-here** 
  i.e git remote add origin https://github.com/AsifMian/nw.git

- 5. **git push -u origin master**

## Now Your project have been Added to gitHub



# How to Modifiy and  save changes to github repository After

After changing the files 

if you changed the files online then 
{
  better to pull the project

  - **git pull**
 
  or 
 - **git clone repository-address-here**

}

# Run:

- **git add .**

## For evey change you have to commit the change !
-  **git commit -m "New change"**

>>check wheather all changes have been commited

-  **git status**

>>Then run

-  **git push origin master**

# Your changes have been saved to git repository


**How to delete branch**
>> git branch -D branchName

>> git branch -d branchName
   
 OR

>>git push origin --delete branchName

