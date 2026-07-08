## Step 1: Install Git

Download Git from:

Git for Windows

Install it with the default options.

After installation, open Command Prompt or Git Bash and type:

git --version

Example:

git version 2.50.1.windows.1

If you see a version number, Git is installed correctly.

Step 2: Install VS Code

If you don't already have it:

Visual Studio Code

During installation, enable:

✅ Add to PATH

Step 3: Configure Git

Tell Git who you are.

Open Git Bash.

Set your username:

git config --global user.name "Vijay R R"

Set your email (use the same one as GitHub):

git config --global user.email "your_email@gmail.com"

Verify:

git config --list

You'll see something like:

user.name=Vijay R R
user.email=xxxx@gmail.com
Step 4: Create Your First Project

Create a folder.

Example:

GitPractice

Open it in VS Code.

Then open Terminal.

Initialize Git:

git init

Output:

Initialized empty Git repository

Now your folder becomes a Git repository.

Step 5: Create a File

Create:

README.md

Write:

# My First Git Project

Learning Git from scratch.
Step 6: Check Status

Run:

git status

You'll see:

Untracked files:

README.md

Git is saying:

"I see a new file, but I'm not tracking it."

Step 7: Stage the File
git add README.md

Or add everything:

git add .

Now check:

git status

You'll see:

Changes to be committed
Step 8: Commit

A commit is like saving a checkpoint.

git commit -m "Initial commit"

Output:

1 file changed
Step 9: View History
git log

Example:

commit 98asd712...
Author: Vijay

Initial commit
Step 10: Connect to GitHub

Create a repository on GitHub.

For example:

GitPractice

Do not initialize it with a README (since you already have one locally).

GitHub will give commands like:

git remote add origin https://github.com/vijayrr33/GitPractice.git

Run that command.

Step 11: Push to GitHub

Rename your default branch (if needed):

git branch -M main

Then push:

git push -u origin main

Done!

Refresh GitHub.

Your files are online.