# To Push a Project to a GitHub Repository

### Step 1. Initialize Git in Your Local Project Folder  
Use the following command to start version control in your project folder:

```
git init
```

### Step 2. Stage All Files  
Add all files in your project directory to the staging area:

```
git add .
```

### Step 3. Commit the Changes  
Create your initial commit with a message describing the setup:

```
git commit -m "project base setup with toast and readme"
```

### Step 4. Check Status (Optional)  
Verify which files are staged, committed, or untracked:

```
git status
```

### Step 5. Configure Git User (Only Once Per Machine)  
Set your global Git username (if not already configured):

```
git config --global user.name "sanass3258"
```

### Step 6. Check Commit Log (Optional)  
Review your recent commits:

```
git log
```

### Step 7. Add Remote Repository  
Connect your local repository to a GitHub remote URL:

```
git remote add origin https://github.com/sanass32
```

### Step 8. Verify Remote URL  
Ensure the remote URL is correctly set:

```
git remote -v
```

### Step 9. Check Branch  
Check the current branch you are on:

```
git branch
```

### Step 10. Push Code to GitHub  
Push your local code to the GitHub repository on the `master` branch:

```
git push -u origin master
```