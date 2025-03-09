```md
# **GitHub Contribution Guide**

## Step 1: Fork & Clone Repository
1. **Fork** the repo (Team Manager)
2. **Clone** it locally:
```sh
git clone [repo clone link]
```
3. Navigate to the cloned repository:
```sh
cd repo-name
```

## Step 2: Create & Switch Branch
```sh
git branch new-branch  # Create a new branch
git checkout new-branch  # Switch to the new branch
```
**OR**
```sh
git checkout -b new-branch  # Create and switch to the new branch
```

## Step 3: Install & Run Project
```sh
npm install  # Install dependencies
npm run dev  # Start project
```

## Step 4: Make Changes & Push
```sh
git add .  # Stage changes
git commit -m "Your message"  # Commit changes
git push origin new-branch  # Push changes to remote
```

## Step 5: Create Pull Request
1. Go to **GitHub → Pull Requests**
2. Create PR & notify **Team Leader**

## Step 6: Await Approval
Wait for the **Team Manager** to review & merge.

## Step 7: Sync Fork & Update Repository
1. Switch to `main` branch:
```sh
git switch main
```
2. Pull the latest changes:
```sh
git pull origin main
```
3. If working in a forked repository, sync fork:
```sh
git fetch upstream
```
```sh
git merge upstream/main
```

## Step 8: Delete a Branch (If Needed)
**Delete a local branch:**
```sh
git branch -d branch-name
```
If the branch is **not merged**, force delete:
```sh
git branch -D branch-name
```
**Delete a remote branch:**
```sh
git push origin --delete branch-name
```

## Step 9: Delete Repository (If Needed)
1. Go to **GitHub → Settings → Danger Zone**
2. Click **Delete Repository** & confirm.

📌 **Note:**
🚨 **Do not push changes directly to** `main` **branch.** 🚨
Thank you for your contribution! 🚀
```
