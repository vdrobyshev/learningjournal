# Intro to Git

Git is responsible for version control. One can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes.

Git stores data in a series of snapshots. At any moment, the work can resume from any of the previous snapshots. Git will also detect file corruption or loss of information in transit.

In orer to work, Git needs to be installed on the local machine. The local Git repository has three components:

* Working Directory: The actual files reside here.
* Index: The area used for staging
* Head: Points to the most recent commit

Files can be pulled from GitHub via Terminal using git clone <http_address > and then edited using a text coder on the local machine.

After editing is done, Add-Commit-Push (ACP) formula is used to update the files in the GitHub.

For instance: 

-git add README.md

-git commit -m "Why you made the changes"

-git push origin master

