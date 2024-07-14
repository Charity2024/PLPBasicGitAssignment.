### Task 1: Repository Setup

#### GitHub Repository Creation
1. **Log in to your GitHub account**.
2. **Create a new repository** on GitHub:
   - Repository name: `PLPBasicGitAssignment`
   - Initialize with a README file.

### Task 2: Local Setup

#### Local Folder Setup
1. **Create a new folder** on your local machine:
   - Folder name: `PLPBasicGitAssignment`
2. **Open a terminal** or command prompt and navigate to the created folder:
   ```bash
   cd path/to/PLPBasicGitAssignment
   ```

#### Git Initialization
1. **Initialize a new Git repository** in your local folder:
   ```bash
   git init
   ```

#### Connecting to GitHub
1. **Link your local repository to the GitHub repository** you created in Task 1:
   ```bash
   git remote add origin https://github.com/your-username/PLPBasicGitAssignment.git
   ```

### Task 3: Making Changes

#### Create a File
1. **Inside your local folder, create a new text file**:
   - File name: `hello.txt`
   - Content: "Hello, Git!"

2. **Create the file and add content**:
   ```bash
   echo "Hello, Git!" > hello.txt
   ```

#### Committing Changes
1. **Stage the changes**:
   ```bash
   git add hello.txt
   ```
2. **Commit the changes**:
   ```bash
   git commit -m "Add hello.txt with a greeting"
   ```

### Task 4: Pushing to GitHub

#### Pushing to GitHub
1. **Push the committed changes to your GitHub repository**:
   ```bash
   git push -u origin main
   ```

### Task 5: Verification

#### Verify on GitHub
1. **Visit your GitHub repository** in a web browser and confirm that the `hello.txt` file and commit message are visible.

### Submission
1. **Ensure all changes are pushed to your GitHub repository**.
2. **Share the link to your GitHub repository** with the instructor or submit it as per the class instructions.

### Additional Tips
- **Document the steps and commands used** in a text file or in the README of your repository.

#### Sample README Content

```markdown
# PLPBasicGitAssignment

## Repository Setup

1. Created a new repository on GitHub named `PLPBasicGitAssignment`.
2. Initialized the repository with a README file.

## Local Setup

1. Created a new folder on my local machine named `PLPBasicGitAssignment`.
2. Initialized a new Git repository in the local folder using:
   ```bash
   git init
   ```
3. Linked the local repository to the GitHub repository using:
   ```bash
   git remote add origin https://github.com/your-username/PLPBasicGitAssignment.git
   ```

## Making Changes

1. Created a new text file named `hello.txt` with the content "Hello, Git!" using:
   ```bash
   echo "Hello, Git!" > hello.txt
   ```
2. Staged the changes using:
   ```bash
   git add hello.txt
   ```
3. Committed the changes using:
   ```bash
   git commit -m "Add hello.txt with a greeting"
   ```

## Pushing to GitHub

1. Pushed the committed changes to the GitHub repository using:
   ```bash
   git push -u origin main
   ```

## Verification

1. Verified the presence of the `hello.txt` file and commit message on the GitHub repository page.

## Repository Link

[PLPBasicGitAssignment](https://github.com/your-username/PLPBasicGitAssignment)
```

Replace `your-username` with your actual GitHub username in the provided commands and URLs.