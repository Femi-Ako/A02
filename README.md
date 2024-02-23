# A02
# Git, GitHub, and WebStorm Tutorial

## Part 1: Using WebStorm

1. **Download and Install WebStorm**: Visit the WebStorm website and download the version of WebStorm that suits your operating system. Follow the instructions to install it.

2. **Create a New Project**: Open WebStorm and click on 'Create New Project'. Choose the type of project you want to create, name your project, and choose a location to save it.

3. **Navigate the Interface**: Familiarize yourself with the WebStorm interface. The 'Project' window on the left shows your project files. The 'Editor' window in the center is where you write and edit your code. The 'Tool Windows' on the right show various tools like Maven, Gradle, etc.

4. **Run Your Code**: Write some code in the editor. To run your code, right-click in the editor and select 'Run'.

5. **Use Version Control**: WebStorm has built-in support for version control systems like Git. To use it, go to 'VCS' > 'Enable Version Control Integration'. Choose 'Git' and click 'OK'.

## Part 2: Using Git and GitHub
# GitHub Tutorial

## Setting Up GitHub

1. **Create a GitHub account**: Visit GitHub and sign up for a new account if you don't have one already.

2. **Download Git**: Visit the Git website and follow the instructions to download and install Git on your computer.

3. **Set up Git**: Open your terminal and configure your Git username and email using the following commands:
    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "youremail@example.com"
    ```

## Creating a Repository

1. **Create a new repository**: Click the '+' icon on the top right of your GitHub profile and select 'New repository'. Name your repository, add a description, choose to make it public or private, and initialize it with a README file.

2. **Clone the repository**: Navigate to the main page of the repository and click on the 'Code' button. Copy the URL and clone it to your local machine using the following command in your terminal:
    ```bash
    git clone "URL"
    ```

## Making Changes and Committing

1. **Make changes**: Navigate to the cloned repository on your local machine and make your changes.

2. **Stage the changes**: Add the changes to the staging area using the following command:
    ```bash
    git add .
    ```

3. **Commit the changes**: Commit the changes with a message describing what you've done using the following command:
    ```bash
    git commit -m "Your message"
    ```

## Pushing Changes and Updating Your Repository

1. **Push the changes**: Push your changes to GitHub using the following command:
    ```bash
    git push origin main
    ```
    Replace 'main' with the name of the branch you want to push to if it's not the main branch.

2. **Check your repository**: Navigate to your GitHub repository and you should see the changes you've made.

Remember, this is just a basic tutorial. GitHub has many more features like branching, pull requests, and more. Happy coding!



# Glossary

- **Branch**: A separate version of a repository. It allows you to work on different versions of a project at the same time.
- **Clone**: A copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy.
- **Commit**: A save point in Git. It's a snapshot of your entire repository at a certain time.
- **Fetch**: A command that tells your local git to retrieve the latest meta-data info from the original (yet doesn’t do any file transferring. It’s more like just checking to see if there are any changes available).
- **GIT**: A distributed version control system that lets you track changes to your code over time.
- **Github**: A web-based hosting service for Git repositories.
- **Merge**: Takes the contents of a source branch and integrates it with the target branch.
- **Merge Conflict**: An event that occurs when Git is unable to automatically resolve differences in code between two commits.
- **Push**: Sends your commits to a remote repository.
- **Pull**: Fetches any changes from a remote repository and merges them into your current branch.
- **Remote**: This is the version of a repository or branch that is hosted on a server, most likely GitHub. 
- **Repository**: A directory or storage space where your projects can live.

# Commit Messages

When making commits, it's important to have clear messages. Here are some examples:

- **Task**: Create Repository
- **Feature**: Added workflow for using GitHub
- **Fix**: Changed README.md for definition of terms
