# GitPractice
## Info:  
This repository is to be used to help the user practice their git techniques as far as we used them. We are assuming no git knowledge coming in, but a small amount of programming knowledge. If there is any confusion, the ```git --help``` command will always be there.  

## What to do:  
### Obtaining code: 
Clone the repository:
```
git clone https://github.com/Marine-Robotics-Club/GitPractice.git
```
### People practice: 
Next, the people folder is to practice using Git branch and merge techniques. We will be adding your name to the list of others currently present.   


```
git checkout -b <your name>
```
git checkout is how you will switch branches. The -b indicates we are creating a new branch. The branch name should be an indication on what you are working on. In this case it is adding your name to the list so it is your own name.     
Now that we are on an isolated branch, we will make the changes required. There isn't a ton to work on for this one. First, add a file with set as **\<your name>.txt** and put whatever text you want to inside of it. Next, add your name anywhere in the **list.txt** file. After this, we are done with the modifications. We will move onto how we are going to add these changes to the rest of the repository.  


```
git add -A
```
This command adds all changes to be tracked that you changed. The -A parameter is what specificlly sets everything. You can also use ```git rm``` and other similar commands. As always, see the ```git --help``` command for specifics pas the tutorial.  


```
git commit -m "Your message here"
```
The commit command does what it sounds like. You are commiting to the code as it should have made some change. This can be as simple as finishing up for the night though, it doesn't need to be cohesive. This is not pushing any code github yet, this is just locally saved on your computer.

```
git push orgin <your name>
```
The push command sends your code to the github servers. orgin just indicates that it is going where we got it from, no real need to work with this in what we develop with. Last you have to make sure you choose your branch to send it too. Again in this case the branch is your name, but if you ever forget what it is called, you can always use the ```git status``` or ```git branch``` command. 
### Pull requests:
Now that you have developed all of this code (and tested), you would like it to be included in the master distribution. This is done using a pull request, and whoever maintins the repository will manage any conflict issues. This is done by going to the repository itself, and clicking the pull request tab as seen in the picture below. 
![PullRequest](/images/PullRequest.png)
  

## Extra Reference:  
For fast reference you can check out Githubs own cheatsheat that is attached bellow:  
![Cheatsheet1](/images/github-git-cheat-sheet-1.jpg)
![Cheatsheet2](/images/github-git-cheat-sheet-2.jpg)