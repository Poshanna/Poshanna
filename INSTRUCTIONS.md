# How to Setup Your Animated GitHub Profile README

Follow these steps to set up and customize your new profile README:

## Step 1: Create Your Profile Repository
1. Go to GitHub and click **New repository** (or go to `https://github.com/new`).
2. Set the **Repository name** to match your GitHub username exactly (e.g., if your username is `octocat`, name the repository `octocat`).
3. Make sure the repository is **Public**.
4. Check **Initialize this repository with a README** (you can overwrite it).

---

## Step 2: Add These Files & Customize
1. Clone or open the files from this directory:
   - [README.md](file:///C:/Users/MEDHA%20TRUST/.gemini/antigravity/scratch/github-profile-readme/README.md)
   - [.github/workflows/snake.yml](file:///C:/Users/MEDHA%20TRUST/.gemini/antigravity/scratch/github-profile-readme/.github/workflows/snake.yml)
2. Open `README.md` in a text editor.
3. Replace all the placeholder text (marked with capitals like `YOUR_GITHUB_USERNAME`, `YOUR_NAME`, `YOUR_ROLE`, etc.) with your actual details.
   > [!TIP]
   > You can customize the typing animation lines by editing the `lines=` parameter inside the `herokuapp.com` image URL at the top. Use `+` for spaces and `;` to separate lines.

---

## Step 3: Enable Workflow Permissions on GitHub
Before pushing the files, you need to allow GitHub Actions to write the snake contribution animation to your repository:
1. Go to your repository on GitHub.
2. Click on **Settings** (the gear icon at the top of the repository page).
3. In the left sidebar, click on **Actions** -> **General**.
4. Scroll down to the bottom under **Workflow permissions**.
5. Select **Read and write permissions**.
6. Click **Save**.

---

## Step 4: Push the Files & Generate the Snake
1. Commit the `README.md` and `.github/` folder to your main branch and push them.
2. In your repository on GitHub, click on the **Actions** tab.
3. Select the **generate animation** workflow in the left sidebar.
4. Click **Run workflow** -> **Run workflow** button on the right.
5. Once the workflow finishes successfully, it will create a new branch named `output` containing the contribution snake animation!
6. Go back to your main profile page (`github.com/YOUR_USERNAME`) and enjoy your beautiful new interactive README!
