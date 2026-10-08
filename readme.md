1. Download Git
Go to the official Git website:
Git for Windows
Download Git for Windows.
2. Run the installer
Open the downloaded .exe file.
Click:
Next → Next → Next
You can keep the default options for most screens.
3. Important installation options
When you reach "Choosing the default editor", you can leave the default option or select Visual Studio Code if it appears.
When you reach "Adjusting the name of the initial branch", choose:
Override the default branch name
and enter:
main

For the PATH option, select:
Git from the command line and also from 3rd-party software
Keep the remaining options at their defaults.
4. Finish installation
Click:
Install → Finish
5. Verify Git installation
Open Command Prompt or PowerShell and run:
git --version

You should get something similar to:
git version 2.x.x

6. Configure your name
Run:
git config --global user.name "Your Name"

Example:
git config --global user.name "Muhammad Sami Khan"

7. Configure your email
Run:
git config --global user.email "your@email.com"

Use the email associated with your GitHub account if you're going to use GitHub.
8. Check configuration
git config --global --list

You should see your:
user.name=...
user.email=...

Git is now installed and configured.