## 🚀 Workflow: Deploying Project to GitHub

| Step | Action | Description |
|------|--------|-------------|
| 1 | **Open VS Code** | Launch Visual Studio Code and open the project folder `IntroToDataStructures_Workshop`. |
| 2 | **Open Terminal** | Use either **PowerShell** or **Git Bash** inside VS Code (``Ctrl + ` `` shortcut). |
| 3 | **Initialize Git** | Run `git init` to create a new Git repository in your project folder. |
| 4 | **Create .gitignore** | Add a `.gitignore` file to exclude unnecessary files (e.g., `.ipynb_checkpoints/`, `__pycache__/`, `.DS_Store`). |
| 5 | **Stage Files** | Run `git add .` to stage all project files for commit. |
| 6 | **First Commit** | Run `git commit -m "Initial commit: Intro to Data Structures Workshop"`. |
| 7 | **Connect to GitHub** | On GitHub, create a new repository named `IntroToDataStructures_Workshop` (leave it **empty**: no README, .gitignore, or license). |
| 8 | **Add Remote** | Run `git remote add origin https://github.com/<your-username>/IntroToDataStructures_Workshop.git` (replace `<your-username>` with your GitHub handle). |
| 9 | **Push to GitHub** | Push the code with `git branch -M main` then `git push -u origin main`. |
| 10 | **Verify on GitHub** | Visit your repo URL to confirm the code, notebook, requirements, and datasets are uploaded successfully. |
