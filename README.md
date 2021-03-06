# Intro Git / GitHub Workshop


Welcome to the Introduction to Git and GitHub README. This page will tell you everything you need to know about the basics of **git** and **github**. Both of these tools are widely used in industry, schools, and many different disciplines.

Within this repository (AnIntroToGitAndGitHub), you will find this README along with one other file: Change.txt. 

Now, before we get started, let's talk a little bit about what a README file is for. In short, the first thing you want to do whenever looking at a new repository for the first time is to look at the README. (i.e. exactly what you are doing right now!) Common items in a README include instructions on how to get involved in the project, how to get the source code onto your local environment (computer), or what the repository/code base does. This particular README will include info on all three in addition to more general information about Git, GitHub, and further resources on open source development to get you going.

(Note, if you have basic experience with Git and GitHub you might want to begin with a more advanced GitHub repository/tutorial on my page: [PrisonersDilemmaCSWorkshop](https://github.com/fordc5/PrisonersDilemmaCSWorkshop)).

So let's dive right in.

### Before you begin - Create an account

i) If you already have a GitHub account and git installed, great! (Go ahead and skip to Step One) If not, follow along below.  

ii) In the upper right of this page you should see a **Sign up** button. Select that.  

iii) Enter in your personal details...

iv) Once you are finished come back to this page. 

v) Now open up your terminal. We are going to install git if you do not already have it. (On a mac you can check what version of git you have installed by running git ```$ git --version```)  

vi) You are going to run two commands to install git. The first is installing some software called [Homebrew](https://brew.sh/). Homebrew is awesome, you'll use it for installing lots of cool stuff in the future. The second command uses Homebrew to install git.

```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew install git
```

After this is done, run:
```
$ git --version
```
To make sure git installed.

vii) Configure your username and email by typing
```
$ git config --global user.name "Tiago Ford"
$ git config --global user.email "tford@email.com"
```

### Step One - Get the source code onto your computer

(At this point you might want to open up two windows so you can follow along with these instructions and work on other screens at the same time).

i) Fork this repository. Do this by clicking the Fork button in the upper right of this page. What this does is copy the current version of this repository onto your own GitHub page! (You might have to verify your email first if you just set up a new GitHub account).
1. You might then see a pop up that asks where you would like to fork the repo. Select your username/profile if this shows up.
2. Now navigate to **your profile** page and you should see this forked repository sitting there. Go ahead and click on it.

ii) At this stage, all of the code it still in the cloud, but we want to get a copy of the files down onto your personal computer. We will do this by **cloning** your forked version locally.
1. Open up terminal and cd to your workspace. (i.e. something along the lines of ```$ cd Documents/ComputerScience/CS52/workspace/```)
2. Now go back to the repository on your page and click **Clone or Download** button.
3. A little pop-up will apear. Click the **Copy to clipboard** button on the right side.
4. Open your terminal and type ```$ git clone [paste your url here]```. 

iii) open the Change.txt file in the text editor of your choice
1. e.g. if you have sublime, open sublime, go to File -> Open -> Find and select the Change.txt file

Congratulations for making it this far! You have completed the hardest part. Often times with open source projects, getting the code locally without any bugs in the appropriate software is half the battle.

### Step Two - What this code does

i) So, what code/files should you change?

Well, there's sort of two answers here. The first is that you really could change anything you want! You could turn these files into a website, add files, delete files, or anything else you can imagine! That's the exciting part about open source code.

But for contributing to this specific repository you have to follow a set of guidelines. You can find these in the next section.


### Step Three - How to contribute

This might be the most important section of any major GitHub repository. This is because you can make all sorts of changes and improvements to someone else's code, but if you don't follow the posted guidelines, when you 'submit' your changes, they might get rejected. Often times owners of the repository will specify things from spaces vs. tabs, to what parts of the code they want you to touch, to what other developers you can reach out to, etc...

i) Editing the text file
1. Open up the file Change.txt in your favorite text editor.
2. Make some changes to it. Add your name, a joke, or your favorite band.  

ii) **add**, **commit**, **push** 
1. So you've made your changes, and now you're ready for the whole world to see it.
2. After you have tested your code to make sure there are no bugs, save it all and open up the terminal.
3. Use the command cd to navigate to the directory you are working in. (i.e. it might look something like ```$ cd Documents/ComputerScience/CS52/workspace/AnIntroToGitAndGitHub```)
4. Next, run ```$ git add .``` (note the period after the space)
5. The run ```$ git commit -m "[some sort of descriptive message here]"```
6. And finally run ```$ git push```
7. You might now be asked to type in your username and password. This makes sense because how else would your terminal know where to push the code!

iii) Make a **pull request** to this repository
1. Sweet, we're almost there. Navigate back to your GitHub page and refresh it. Remember that repository we made appear on your profile? Open that up and near the top click **commits**. You should see the commit you just made at the top! If you click it you will see a summary of the changes you made to the repository.
2. Now it's time to 'submit' your changes. What this is called is a Pull Request, or PR for short. Going back to the main page of your repository you should see a button called **New Pull Request**. Select this.
3. You will be able to see what branches you are working on and again a summary of the changes you made. Go ahead and click the green **Create Pull Request** button. You will see another page summarising your PR. Click the **Create pull request** button again.
4. Your pull request has now been sent to the owners of the repo. I'll quickly check your changes to make sure you aren't breaking anything, and then I'll accept! Just like that the code you wrote is live on the internet. 

Congratulations! Your first open source development contribution!



### Resources

i) Check out this [link to a more advanced tutorial on open-source software development](https://github.com/fordc5/PrisonersDilemmaCSWorkshop) if you'd like more practice.

ii) Git resources:  
Git tutorial: https://try.github.io/levels/1/challenges/1  
Git cheat sheet: https://www.git-tower.com/blog/git-cheat-sheet  

iii) GitHub resources:  
Popular projects on GitHub: https://github.com/explore  
GitHub's help page: https://help.github.com/articles/git-and-github-learning-resources/  

iv) Open source resources:  
Good resource for first-timers: http://www.firsttimersonly.com/  
Udacity tutorial: https://www.udacity.com/course/how-to-use-git-and-github--ud775  

But seriously, open source development is a steep learning curve. It may be tough at first, but jumping head first into a project will get you to where you want to be faster than any series of tutorials will.  

v) Other neat projects/sites:  
You get a ton of cool, free stuff as a student on GitHub. Check it all out here: https://education.github.com/pack  
