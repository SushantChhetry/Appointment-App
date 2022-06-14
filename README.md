# Appointment-App
An web application to create appointments.

# Getting started with Github

* Make Github Profile
* Accept collaborater invitation for the Github repository
* Clone the Github repository into your device

## First Thing First

### Make sure that Git is installed in your computer

In your command prompt type
 ```
 git --version 
 ```
 If you see a version of Git, you are good to proceed to the other steps. Otherwise, install git in your device.
 
 [How to download Git](https://github.com/git-guides/install-git)
 
 ### Collaboration
 
 Suppose we start working and we need help, then click on **New Issue** button and write the title and description.
 
 ![New Issue](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rasnvg01wtaxt35p4oa8.png)
 
 ![Issue Fill](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/mgf8tpr35i1dbzpnno2l.png)
 
 Then if you can help, comment on it.
 
 ### Start Working
 
 To work on the project on your local device you need to **clone** it.
 
 ![clone](https://user-images.githubusercontent.com/60019004/173660317-379077c8-396c-4ce9-b4ba-fb96e9e75bf3.png)
 
 Then create a new folder and using the command prompt go into the folder.
 
 ```
 cd folderName
 ```
 
 Then clone the project into your folder.
 ```
 git clone "http://(the link copied)"
 ```
 
# Github workflow

This is the typical workflow for making changes in the project.

1. Create a branch
2. Make changes (adding files/codes/assets/resources)
3. Create a pull request
4. Address review comments
5. Merge your pull request
6. Delete your branch

## Step 1: Create a branch

It is not a good practice to work on the Master branch. So we need to create our own branch to work on and make changes. 

![branch](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/f6yne1wb24kctulcw654.png)

## Step 2: Work on the branch locally

After creating the branch, pull it into your local device by typing the following code in your terminal.

```
git pull
```

Now that you have the branch that was created by you to work on, switch into the branch by typing the following code.

```
git checkout yourbranchnamehere
```
To check if you are in the correct branch type.
```
git branch
```
Now start coding and making changes! 

When you are ready or done coding for the day, stage the changes:
```
git add .
```
This will add all the changes to the staging area. Now you have to commit them:
```
git commit -m "What Did you Fix"
```
Now push it to our repository
```
git push
```
## Step 3: Create a Pull request

Once you have pushed it go to Github online and into your branch in the repository where you can see the pull request. Click on **Compare and Pull Request** button

![pull request](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/spgnh14xpr1wnqlis2k3.png)
![next step pull](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9nsmrf4fbqloojq41tk0.png)

These steps should be fine for us. But if you want to learn more about the workflow

[Click Here](https://www.freecodecamp.org/news/how-to-use-git-and-github-in-a-team-like-a-pro/)
