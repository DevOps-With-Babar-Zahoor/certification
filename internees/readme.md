# Certification Repository

Welcome to the Certification Repository for [Open Source Foundation of Pakistan (OSPF)](https://osfp.org.pk/)!

This repository is designed to manage certification materials for our interns. Each intern will have their own folder within the "internees" directory to store and organize their certification-related documents.

## Process for Interns

### 1. Forking the Repository

1. Fork this repository to your own GitHub account using the "Fork" button in the top right corner of this page.

### 2. Cloning the Forked Repository Locally

1. Clone your forked repository to your local machine or open in **codespace**:

   ```bash
   # if you are not using codespace then follow as following, if codespace is being using then skip this step and go to step 3.
   git clone https://github.com/your-username/certification.git
   cd certification
   ```

### 3. Creating a Folder with Membership ID

1. Inside the `internees` directory, create a folder with your membership ID:

   ```bash
   mkdir internees/<your membership ID>
   # For example your membership id is DOBZ000001 then run the following command
   # mkdir internees/DOBZ00001
   ```

### 4. Adding Files and Making Changes

1. Add any necessary files, documents, or code related to your certification inside your folder.
2. For example: as the task 01 of the linux exercise is completed, then create a file Linux.md and if already exists (if your had already completed some tasks and this file is already creadted then just edit.
   > add your completed tasks' closed issue URL from [Internee-Tasks-Validataion](https://github.com/DevOps-With-Babar-Zahoor/Internee-Tasks-Validataion), and keep adding lines. After every line addition, create a pull request be following the procedure below. And make sure all completed, validated and closed issue tasks are present in the list.

### 5. Committing and Pushing Changes (after every task completion)

1. Commit your changes and push them to your forked repository:

   ```bash
   git add .
   git commit -m "Add files for certification"
   git push origin main
   ```

### 6. Creating a Pull Request

1. Go to your forked repository on GitHub.
2. Click on the "New pull request" button.
3. Ensure that the base repository is set to the main certification repository.
4. Create the pull request.

### 7. Approval and Merge

1. The repository owner will review your pull request.
2. If everything looks good, they will approve and merge your changes into the main repository.

### 8. Keeping Your Fork Updated

1. To keep your forked repository up-to-date with changes from the main repository:

   ```bash
   git fetch upstream
   git merge upstream/main
   git push origin main
   ```

Replace "upstream" with the alias for the main repository.

Thank you for contributing to our certification process! If you have any questions or encounter issues, feel free to reach out to .
