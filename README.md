# Version Control with Git and GitHub

Welcome! In this course you will learn how to control versions and collaborate on web development projects using Git and GitHub. In addition, we will see how to publish a web page with GitHub Pages. Everything you need to manage projects and work as a team efficiently.

## Learning Units

### 1. Terminal, Git and GitHub
Here I will teach you how to:
- Create a remote repository on GitHub.
- Control the versions of a project.
- Publish a web page using GitHub Pages.

### 2. Collaborative Work and GitHub Pages
In this unit you will learn:
- The collaborative workflow with Git.
- How to manage changes, branches and conflicts in collaborative projects.
- How to use GitHub Pages for publishing websites.

## Required Tools

- **Firefox**: Recommended browser to view and test the web page.
- **Visual Studio Code**: The code editor we will use.  [Download VSCode](https://code.visualstudio.com/).
- **Git Bash** (for Windows) / **Terminal** (for Linux and Mac): Command line tools to run Git.
- **Git**: Version control software. [Download Git](https://git-scm.com/downloads).
- **GitHub / GitHub Pages**:  Platform for hosting code and website. [GitHub](https://github.com/).
- **Xcode** (for Mac): Used to install and update Git on macOS. [Download Xcode](https://imageoptim.com/changelog.html).

## Let's get started!

This course is designed to help you understand not only how to control versions, but also how to effectively collaborate with others on a project and share your work with the world through GitHub Pages.

---

## Step-by-Step for Version Control and Collaboration

### 1. Initial Setup

First, make sure you have Git installed. Then set your name and email in Git:

- git config --global user.name "Your Name"
- git config --global user.email "youremail@example.com"

### 2. Create a Local Repository

To start a repository in your project, use the following command inside your project folder:

- git init
  
This will start version control in the folder you are working in.

### 3. Create a Remote Repository on GitHub

1) Sign in to GitHub.
2) Create a new repository, give it a name, and select "Create repository".
3) Then link your local repository to GitHub using the following command (replace with your URL):

- git remote add origin https://github.com/youruser/your-repository.git

### 4. Make Changes and Push Them to GitHub

1) Add files to the staging area:
   
   - git add .
     
3) Make a commit with a message describing your changes:
   
   - git commit -m "Description of changes"
     
4) Push your changes to the remote repository on GitHub:
   
   - git push -u origin main
   
### 5. Clone an Existing Repository

If you're collaborating on a project and need to clone an existing repository:

- git clone https://github.com/user/project.git

### 6. Collaboration: Pull and Push

To work with others, it's always important to get the latest changes before making edits:

- git pull origin main

After making your own changes, add and push with:

- git add .
- git commit -m "Description of changes"
- git push origin main

### 7. Publish a Web Page with GitHub Pages

To publish your project as a web page:

1) Go to the Settings tab in your GitHub repository.
2) In GitHub Pages, select the main branch and the /root folder.
3) You're done! Your page will be available at https://youruser.github.io/your-repository/.

