# Github session

Welcome to our session. let's get started with github. Before we jump into it we need to know a few things and terms related to it. You can see the README.md for resources related to git/github. Now let us get started with Open Source.

## Git

Git is a widely-used version control system used to manage code. Nearly 70% of developers use Git, according to a Stack Overflow survey.

Git allows you to save drafts of your code so that you can look back at previous versions and potentially undo complicated errors. A project managed with Git is called a repository.

A repository contains all of the files and folders associated with your project. It also includes the revision history of each file. The file history is a series of snapshots in time, known as commits. A commit tells Git that you made some changes which you want to record.

When you make a commit in Git you will see “commit to main.” This is referring to the default branch, which can be thought of as the production-ready version of your project.

## Github

What is GitHub?
Git and GitHub are the same thing…right? Not exactly.

GitHub is a popular hosting service for Git repositories. GitHub allows you to store your local Git repositories in the cloud. With GitHub, you can back up your personal files, share your code, and collaborate with others.

In short, GitHub is a tool for working with Git. There are other services to host Git repositories, but GitHub is a trusted, free service used by organizations across the world, big and small.

To use GitHub and GitHub Desktop, you will need a GitHub account.

If you already have a GitHub account, continue to the next section (GitHub Desktop). Otherwise, follow these steps:

In your browser:

- Open a new browser tab.

- Navigate to [github](https://github.com)

- Create an account.

After you sign up, you will receive a verification email. Be sure to verify your email address to GitHub by following the instructions in that email.

## Github Desktop

GitHub Desktop
Once you have your GitHub account set up, you are ready to install GitHub Desktop.

In your browser:

- Open a new browser tab.

- Navigate to [github desktop](https://desktop.github.com)

- Download GitHub Desktop.

Once installed, open the GitHub Desktop application. You should see a screen prompt for sign In . Sign In and complete the configuration process.


| Sign In    | Configure Git | 
|------------|---------------|
| <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-welcome.jpg" width="500"> | <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-configure.jpg" width="500"> |

### Creating a Repository in GitHub Desktop and publishing to Github

Follow below steps to create a new repo on your local machine and push it to your remote account on github.

| Create new repository  | Repo will be on your local computer | 
|------------------------|-------------------------------------|
| <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-repo.jpg" width="500"> | <img src="imgs/github.png" width="500"> |

  Now that you have created your local github repo, push it to github. It will allow others to see your work and for collaborations. You can view your local repo now on github and share it with others.
  

| Publish your repo to remote | Published on github | 
|-----------------------------|-------------------------------------|
| <img src="imgs/github4.png" width="500"> | <img src="imgs/github5.png" width="500"> |

### Commit in GitHub Desktop

Make changes to your repo then add and commit the changes you made.

To make our first commit, we first need to modify one of the files in our repository.

- Navigate to the local folder on your Desktop (or wherever you chose to locate it). You’ll notice that the only file contained in this folder is a README.md file.

- Open this file with your preferred text or code editor and write a personalized message. For instance, we can write the following:

- When we’re ready to commit, we can simply click “Commit to main.

<div align="center">
  
  | Make changes to the file  & Commit your changes | 
  |-------------------------------------------------|
  | <<img src="imgs/github8.png" width="700" >|
  
 </div>

Congratulations! You just learned how to perform a Git commit using GitHub Desktop.

Your commit is currently local to your computer. If you want the changes to the README file to show on GitHub, you must click “Push origin” on the next screen.

Now when you navigate to your codecademy-git-test repository on github.com, you should see your updated README file:
| Push origin  | Published on github | 
|--------------|-------------------------------------|
| <img src="imgs/github9.png" width="500"> | <img src="imgs/github10.png" width="500"> |

### Fetch/Pull in GitHub Desktop

When you collaborate with other people on a repository, you will want to see what everyone is working on and update your files with the most up-to-date changes.

In Git, fetching is the process of updating your files with the most recent changes. Luckily, GitHub Desktop makes fetching changes easy.

Let’s suppose that someone made an update to our README file from the previous example. After making changes scroll down & click the green commit button.

You should click “Fetch origin” so that the changes are fetched in Github desktop :


| Update the readme file  | Fetch your remote changes | 
|-------------------------|---------------------------|
| <img src="imgs/github11.png" width="500"> | <img src="imgs/github13.png" width="500"> |

Next, you should click “Pull origin” so that the changes are reflected in the files on your local machine:

Now, navigate to the local folder on your Desktop (or wherever you chose to locate it). If you open the README file, you will notice that the changes made to the file are correctly shown:

| Pull your remote changes  | See updated local readme file | 
|---------------------------|---------------------------------|
| <img src="imgs/github14.png" width="500"> | <img src="imgs/github15.png" width="500"> |

### Fork and Clone a repository

To fork a repository go the repo on github website and the click on Fork.

This will create a fork in your remote github.

<div align="center">
  
  | Create a Fork of the repository you want to contribute  | 
  |---------------------------------------------------------|
  | <<img src="imgs/github16.png" width="750" >|
  
 </div>

Now, create a clone of the forked repository in your github desktop:

First click on add a clone then choose from the list of forked repository you have and then click on clone. It will create a copy of the repo on your github desktop which will be stored locally on your computer.


| Clone the repository  | Complete the process | 
|-----------------------|----------------------|
| <img src="imgs/github18.png" width="500"> | <img src="imgs/github17.png" width="500"> |

### Making Changes to the forked repository & submitting a PR

Add a file your_name.txt to the forked repo. Go to your remote github and add a file. Now edit that file with some text and then Commit your changes.
You can click on contribute and create pull request as your forked repo is ahead of the original repo. So your PR will bring it on the same level and synchronize it.


| Make changes to your fork and commit  | How to open a pull request| 
|---------------------------------------|----------------------|
| <img src="imgs/github20.png" width="500"> | <img src="imgs/github21.png" width="500"> |

Now you will be directed to an option to create a pull request. once you do that it will notify the owner of the repo in the pull request section. Now they will review your changes.

| Create your first PR  | Your PR can be seen in the pull request section | 
|---------------------------------------|---------------------------------|
| <img src="imgs/github22.png" width="500"> | <img src="imgs/github23.png" width="500"> |

### Getting your PR merged successfully !

Now , the owner can navigate to PR sectiona and review your changes, if they approve of your PR , it will be merged into the main branch and tadaaa!!!! You just created your first PR. Get yourself going forward <3🚀🚀🚀

The owner can also request changes if necessary any actions to your PR will be notified. Always Keep patience.


| How owner will see your PR & review it | Your first PR successfully merged! | 
|----------------------------------------|---------------------------------|
| <img src="imgs/github24.png" width="500"> | <img src="imgs/github25.png" width="500"> |

### Updating your Fork with the Original repo

When many people work on a repo it can get messed up. Hence it is necessary to update your fork constatntly and pull those changes to your local repo. Before you can push any changes make sure to pull changes from the working repo.

Below is how you update your branch. After updating it , you must pull those changes through github desktop.

<div align="center">
  
  | Update your Fork constantly to stay on par with the source repo| 
  |----------------------------------------------------------------|
  | <<img src="imgs/github19.png" width="750" >|
  
 </div>


## Happy hacking ! way to go. Welcome to OPEN SOURCE ❤️🙌

