<h1>Git and Github</h1>

<h3>What is git ?</h3>

Git is a distributed version control system used for software development and other tasks. It essentially allows developers to track 
changes to source code, collaborate with others and lastly manage multiple versions of a project over time. It uses a decentralized method, 
where each developer maintains a local copy of the codebase, which can be combined with other copies. This brings more of a flexible workflows
and simple collaboration between developers, with the changes being made independently or together.

<img width="827" alt="Github_Git_Diagram" src="https://user-images.githubusercontent.com/126012715/232328440-5927bea8-1134-4d66-af76-479df058506a.png">

<h3>What is GitHub ?</h3>

A web-based platform that provides hosting Git repositories, as well as tools, project management and software development workflows. It has become
one of the widely used platforms for open-source development and collaboration.

GitHub allows developers to host their Git repositories on the platform, making is simple share their code with the broader community. Providing 
a web-based interface for managing repositories, tracking bugs, and tools such as pull requests and code reviews.

<h3>What is the difference between the two ? How do they interact ?</h3>

Git is a distributed version control system used to manage changes to source codes, whereas GitHub is a web-based platform providing a host of repositories.
The key differences are, functionality, as Git provides branching, merging and committing changes. GitHub includes additional top ups such as collaboration tools, 
issue tracking and integration with other services. Hosting is within Git which uses command line tools used locally within the developers system, where as GitHub 
requires Git to host it on the web platform. They are related as they both serve each other's purposes.


<h3>Benefits of Version Control ?</h3>

Benefits include:

Version history , which provides a complete history of changes made to the source codes over time. thus allowing developers to track the changes like when and what being made.

Collaboration - Allows multiple developers to work on a codebase together simultaneously, without the interference of others, making it easier for complex projects.

Branching and merging - Multiple branches can be made of a codebase, thus being used for parallel development, feature experimentation and bug fixing.

And others such as backup and recovery, traceability and auditability, and coding quality and testing.

<h3>Main Git Commands</h3>

The following are the main commands used within Git and how a repository is setup.

`git init` - Initialises new repo on localhost

`git status` - To check what was added to be sent to GitHub

`git add -`  - Adds all files/folders from the current location

`git commit -m "first commit"` -m is to put any logical message

`git branch -M`  - Main To change branch from master to main

`git remote add origin git@github.com:[user]/[repo].git` - Connects localhost to GitHub repo

`git push - u origin main` - Pushes the code upstream from localhost to GitHub

`git merge` - Putting a forked history back together again. This command lets you take the lines of development created by the git branch and integrate them into 
a single branch. 

`git pull` - Is used to fetch and download content from a remote repository and update the local repo to match the content.

<h3>What are branches ?</h3>

A branch is a unique set of code changers with a unique name. One or more branches can be within each repository. The main branch, where all changes eventually get merged back into is called master.
Which is seen on github, and is the official working version of the project. The master branch cannot be rendered as it will affect the other people, and merge conflicts could occur.

<h3>What is a pull request ?</h3>

A pull requests are mechanisms for a developer to notify team members that they have completed a feature. Once it is ready, the developer files a pull request through their Github account. 
It lets you tell others about the changes you have pushed to a branch in a repository. All reviews and changes can be made before the commits are merged into the base branch.

<h3>How do DevOps engineers interact and use Git/Github ?</h3>

DevOps engineers use Git and GitHub a lot in their work to manage and collaborate on source code, automate builds and deployments, and monitor and analyze performance metrics.
These include:

- Version Control: Keeping tracking of source code and configurations.
- CI/CD: To automate the build, test and deploy
- Infrastructure as code (Iac): Managing files, scripts, and using tools like Terraform and Ansible.
- Monitoring and Analytics: Track issue and pull requests related to code changes and deployments.
