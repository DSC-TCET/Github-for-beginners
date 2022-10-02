# Github session

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
| <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-repo.jpg" width="500"> | <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-create-repo.jpg" width="500"> |

| Publish your repo to remote | Published on github | 
|-----------------------------|-------------------------------------|
| <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-publish-repo.jpg" width="500"> | <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-github-repo.jpg" width="500"> |

### Commit in GitHub Desktop

Make changes to your repo then add and commit the changes you made.

To make our first commit, we first need to modify one of the files in our repository.

- Navigate to the local folder on your Desktop (or wherever you chose to locate it). You’ll notice that the only file contained in this folder is a README.md file.

- Open this file with your preferred text or code editor and write a personalized message. For instance, we can write the following:

- When we’re ready to commit, we can simply click “Commit to main.

| Make changes to the file  | Commit your changes | 
|---------------------------|---------------------|
| <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-readme.jpg" width="500"> | <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-commit.jpg" width="500"> |

Congratulations! You just learned how to perform a Git commit using GitHub Desktop.

Your commit is currently local to your computer. If you want the changes to the README file to show on GitHub, you must click “Push origin” on the next screen.

Now when you navigate to your codecademy-git-test repository on github.com, you should see your updated README file:
| Push origin  | Published on github | 
|--------------|-------------------------------------|
| <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-push-origin.jpg" width="500"> | <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-github-readme.jpg" width="500"> |

### Fetch/Pull in GitHub Desktop

When you collaborate with other people on a repository, you will want to see what everyone is working on and update your files with the most up-to-date changes.

In Git, fetching is the process of updating your files with the most recent changes. Luckily, GitHub Desktop makes fetching changes easy.

Let’s suppose that someone made an update to our README file from the previous example. The README file now looks like this:

You should click “Fetch origin” so that the changes are fetched in Github desktop :


| Update the readme file  | Fetch your remote changes | 
|-------------------------|---------------------------|
| <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-new-readme.jpg" width="500"> | <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-fetch-origin.jpg" width="500"> |

Next, you should click “Pull origin” so that the changes are reflected in the files on your local machine:

Now, navigate to the local folder on your Desktop (or wherever you chose to locate it). If you open the README file, you will notice that the changes made to the file are correctly shown:

| Update the readme file  | Fetch your remote changes | 
|-------------------------|---------------------------|
| <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-pull-origin.jpg" width="500"> | <img src="https://content.codecademy.com/articles/Git-and-GitHub-Desktop/what-is-git-new-readme-local.jpg" width="500"> |

