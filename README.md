# A02
HW02 for IT117

PART 1: Directions on Using Visual Studio Code


STEP 1: Download VScode
1. Open your web browser.Go to the official VS Code website:   https://code.visualstudio.com/
2. Click the Download button.
3. Choose your operating system:
    Windows
    macOS
    Linux
4. Wait for the installer to finish downloading.


STEP 2: Install VScode (I did it on mac so thats how I will show it)
1. Open the downloaded file
2. Drag Visual Studio Code into your Applications folder.
3. Open it from Applications. If prompted, click Open.


STEP 3: Install Java
1. To install java you can go to: https://www.oracle.com/java/technologies/downloads/ OR https://adoptium.net/
2. Download the latest JDK (Java Development Kit). Run the installer and follow the instructions.
3. Make sure Java is added to your system PATH. You can also verify installation by opening the terminal and typingg java --version. Basically it will tell you what version of git or vscode you have and if you get nothing back then that means you don't have any version of the app.


STEP 4: Install Java extensions to VScode
1. Open VS Code.
2. Click the Extensions icon (left side).
3. Search for: Extension Pack for Java. Click Install.


STEP 5: Download Git/Github
1. Go to https://github.com/
2. Click Sign Up. Create your account.
3. Go to https://git-scm.com/downloads download for your operating system.
4. Run the installer (default settings are fine). If you want to verify installation go to terminal and type git --version.


STEP 6: Configure Git 
1. Configure Git (First-Time Setup): In Command Prompt or Terminal: git config --global user.name "Your Name" git config --global user.email "your_email@example.com"


STEP 7: Sign in to Gitihub on VScode
1. Open VS Code.
2. Click the Account icon (bottom left). Click Sign in with GitHub.
3. Log in through your browser. Authorize VS Code.


STEP 8: Create a Repo on Github
1. Go to https://github.com
2. Click the + in the top right. Click New repository.
3. Enter a repository name (example: A02). Click Create repository.


STEP 9: Connect project to Github
1. Open your project folder in VS Code. Click Terminal → New Terminal. Type:
    git init
    git add .
    git commit -m "Initial commit"
2. Copy your repository URL from GitHub. Connect it:
    git remote add origin https://github.com/yourusername/repositoryname.git
    git branch -M main
    git push -u origin main


STEP 10: Making Updates
1. After editing your files:
    git add .
    git commit -m "Updated files"
    git push
2. To download updates from Github you can do a git pull by typing "git pull" into the terminal.



Part 2: Glossary

• **Branch**: A separate version of a project where you can work on new features or changes without affecting the main version of the code.

• **Clone**: Copying an existing project from GitHub onto your local computer so you can work on it.

• **Commit**: A saved snapshot of your project at a specific point in time. It records changes along with a message describing what was updated.

• **Fetch**: A command used to download updates from a remote repository without automatically merging them into your current work.

• **GIT**: A version control system that tracks changes in your code and allows multiple people to collaborate on a project.

• **Github**: A cloud-based platform that hosts Git repositories and allows developers to store, manage, and share their code online.

• **Merge**: The process of combining changes from one branch into another branch.

• **Merge Conflict**: An issue that occurs when Git cannot automatically combine changes from different branches because the same part of a file  was edited differently.

• **Push**: A command used to upload your committed changes from your local computer to a remote repository on GitHub.

• **Pull**: A command that downloads changes from a remote repository and automatically merges them into your current branch.

• **Remote**: A version of your repository that is hosted on the internet like github.

• **Repository**: A project folder that contains all files, history, and version tracking information managed by Git.



