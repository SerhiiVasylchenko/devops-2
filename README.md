1. Clone the repository to your local machine
    - Copy the repository URL from GitHub.
    - Open your command-line interface (CLI) and navigate to the directory where you want to store your project.
    - Type the following command to clone the repository: git clone <repository URL>
    - Press Enter to clone the repository to your local machine.

2. Create a development branch
    - Navigate to the project directory on your local machine using your CLI.
    - Type the following command to create a new branch called "development": git checkout -b development
    - Press Enter to create the new branch.

3. Commit changes to the development branch
    - In your CLI, type the following command to add the new file to the staging area: git add README.md
    - Press Enter to add the file.
    - Type the following command to commit the changes to the development branch: git commit -m "Add README file"
    - Press Enter to commit the changes.

4. Merge the development branch into the main branch
    - Type the following command to switch to the main branch: git checkout main
    - Press Enter to switch branches.
    - Type the following command to merge the development branch into the main branch: git merge development
    - Press Enter to merge the branches.
    - If there are any merge conflicts, resolve them in your text editor and commit the changes.