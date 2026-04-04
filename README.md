# Git-practice
Repository created for version control to put my devops assignment 
29-03-2026

1. Check if Git is installed
The quickest way to check is to look for "Git Bash" in your Start menu. If you don't see it, you'll need to download it.

Download: Go to git-scm.com.

Installation Tip: During the setup, when it asks about "Adjusting your PATH environment," make sure you select the option: "Git from the command line and also from 3rd-party software." This prevents the exact error you're seeing now.

2. Add Git to your Environment Variables (If already installed)
If you know Git is installed (e.g., you can find git.exe in C:\Program Files\Git\bin), but PowerShell still complains, follow these steps:

Press the Windows Key and type "Env", then select "Edit the system environment variables".

Click the Environment Variables button at the bottom right.

Under System variables, find the variable named Path, select it, and click Edit.

Click New and add these two paths (adjust if your install location is different):

C:\Program Files\Git\bin

C:\Program Files\Git\cmd

Click OK on all windows.

3. Restart your Terminal
This is the step most people miss! PowerShell won't recognize the changes to the PATH until you completely close and reopen the terminal window.

Quick Verification
Once you've re-opened PowerShell, run:

PowerShell
git --version

4. ssh-keygen -t ed25519 -C "souvik.raha1@gmail.com" --perform this in GITHUB gui


----------------------------------------------------------------------------------------------

git pull
git add
git status
git switch <  >
git push
git commit -m "I have update the file"
git branch -a
git clone git@github.com:souvikraha/Git-practice.git



git checkout -b feature_P6
git push -u origin feature_P6

###################################
