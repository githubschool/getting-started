For msysgit versions older than 1.8.1

First, download git-credential-winstore and install it in your git bin directory.

Next, make sure that the directory containing git.cmd is in your Path environment variable. The default directory for this is C:\Program Files (x86)\Git\cmd on a 64-bit system or C:\Program Files\Git\cmd on a 32-bit system. An easy way to test this is to launch a command prompt and type git. If you don't get a list of git commands, then it's not set up correctly.

Finally, launch a command prompt and type:

git config --global credential.helper winstore
