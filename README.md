
## Setting Up The Repo
1. Clone the repo to your local machine
```sh
   git clone [repo-url]
   ```
  
3. Navigate to the project directory:
 ```sh
   cd JCP26Notebooks or cd [smth]/JCP26Notebooks
   ```
## Working with Git 
Here are some best practices to follow:

1. **Check Your Current Branch:**
   Always make sure you are on the right branch before starting your work.

   ```sh
   git branch
   ```

2. **Pull the Latest Changes:**
   Before creating a new branch or switching to your branch, ensure you have the latest changes from the main branch.

   ```sh
   git checkout main
   git pull origin main
   ```

3. **Create a New Branch:**
   Create a branch from main for your notebooks. (WEEK 1)

   ```sh
   git checkout -b [name]
   ```
   Switch to your branch if you already created your branch. (DO THIS AFTER WEEK 2)
   ```sh
   git checkout [name]
   git merge main
   ```

4. **Add Files and Commit Changes:**
   After making your changes, add the files to staging and commit it.

   ```sh
   git add [notebook name]
   git commit -m "Finished notebook _"
   ```

5. **Push to Branch:**
   Push your branch to the remote repository.

   ```sh
   git push origin [name]
   ```


**IF YOU MADE EDITS ALR BEFORE DOING THESE STEPS CORRECTLY AND RUN INTO error: Your local changes to the following files would be overwritten by checkout: message:**
Just make sure you are in the main branch still and add/commit. Then switch branches and push into your own branch. 
   ```sh
   git branch (make sure ur in main)
   git add [notebook name]
   git commit -m "Finished notebook _"
   git checkout [name]
   git push origin [name]
   ```





