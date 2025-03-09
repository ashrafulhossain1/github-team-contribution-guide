# 🚀 **GitHub Contribution as a Team Member**

## 🎯 Step 1: **Fork the Repository** (Team Leader)
The team manager **forks** the repository to create a copy for collaboration.

---

## 🛠 Step 2: **Clone the Repository** (Team Leader)
```sh
⚡ git clone [repo clone link]
```
### Navigate to the cloned repository:
```sh
cd repo-name
```
---

## 🔧 Step 3: **Set Up the Project**
After cloning, you will be in the `main` branch by default. Follow these steps to ensure the project runs properly:
```sh
📦 npm install  # Install dependencies
🚀 npm run dev  # Run the project locally
```
💡 _If the project runs successfully, proceed to the next step. Otherwise, consult the team leader._

---

## 🌿 Step 4: **Create a New Branch**
Creating a new branch ensures that your changes are **isolated** from the `main` branch.
```sh
🌱 git checkout -b first-branch
```
**OR**
```sh
🌱 git branch new-branch  # Create a new branch
🔄 git checkout new-branch  # Switch to the new branch
```
🎉 Welcome! You are now ready to create or modify any section of this project.

---

## ✨ Step 5: **Make Changes and Push**
After completing your task, add and commit your changes, then push them to your branch:
```sh
📂 git add .
📝 git commit -m "My first contribution added"
📤 git push origin first-branch
```

---

## 🔀 Step 6: **Create a Pull Request**
1️⃣ Go to your **GitHub repository**.
2️⃣ Navigate to the `Pull Requests` tab.
3️⃣ Create a **new pull request** for your branch.
4️⃣ Inform the **team leader** about the pull request.

⚠️ **Important Considerations:**
- If this is your final version, inform the **team leader** so they can review and merge your changes. Once merged, avoid working on this branch further.
-  If further changes are needed, notify the **team leader** before merging. You can continue working on the same branch and push additional commits before finalizing. Once your final changes are complete, inform the **team leader** again.

---

## ✅ Step 7: **Await Approval**
🎉 If you have successfully reached this point, you are welcome! You should now wait for the **team leader** to review and merge your changes. Once approved, your contributions will be added to the **main repository**.

---

## 🔄 Step 8: **Sync Fork and Update for Further Contributions**
If you want to contribute **again**, follow these steps:
1️⃣ Go to your **GitHub repository**, then **sync fork and update** the changes.
2️⃣ In **VS Code**, run the following commands:
```sh
🔄 git switch main
📥 git pull origin main
```
📌 _If you want to create or modify any section of this project again, follow Steps 4–7._

---

## 🗑 Step 9: **Delete a Branch (If Needed)**
If you need to **delete a branch** locally and remotely, use the following commands:

🔻 **Delete a local branch:**
```sh
❌ git branch -d branch-name
```
❗ If the branch is **not yet merged** and you still want to delete it, force delete it with:
```sh
❌ git branch -D branch-name
```

🔻 **Delete a remote branch (Optional):**
```sh
❌ git push origin --delete branch-name
```

---

## ❌ Step 10: **Delete a Repository (If Needed)**
If you need to **delete a repository**, follow these steps:
1️⃣ Go to your **GitHub account** and navigate to the repository you want to delete.
2️⃣ Click on **`Settings`** in the repository menu.
3️⃣ Scroll down to the **`Danger Zone`** section. 🔥
4️⃣ Click **`Delete this repository`**.
5️⃣ Confirm the deletion by **typing the repository name** and clicking the final delete button. ⚠️

---

## 📌 **Note:**
- If you need to modify **previously accepted work**, follow **Steps 4–6** again.
- 🚨 **Do not push changes directly to the** `main` **branch.** 🚨

💙 On behalf of myself, I appreciate you visiting my repository and **thank you for your contribution!** 🙌 Welcome to contribute! 🚀
