# how-to-git

Git is an distributed version control system. It is used for tracking file changes, and serves as a collaboration tool.

### Step 1:

fork this repository.

`https://github.com/AustinMay1/how-to-git`

### Step 2:

clone your forked repo to your local machine.

`git clone https://github.com/YourUsername/how-to-git.git`

### Step 3:

create a local branch to make changes on. name this branch your initials + todays date. for example `AM-11032023`.

2 options here:
+ create and checkout at the same time
    
`git checkout -b new-branch-name`

+ create then checkout

`git branch new-branch-name`

`git checkout new-branch-name`

### Step 4:

make some changes! add your name to the bottom of this document [here.](#check-in)

### Step 5:

stage your changes.

`git add .`

or

`git add filename`

### Step 6:

commit your changes. you should always strive for your commit messages to be very specific about the changes you have made. in this case it doesn't matter to much. just put your initials or something.

`git commit -m "commit message"`

### Step 7:

push your changes to **your branch**. it is important that you specify your branch name in this step.

`git push origin -u your-branch-name`

### Step 8:

open a pull request! navigate to GitHub in your browser and head to your forked repository. You should now see an option to open a pull request to be merged to the main repository.

### Step 9:

Sit back, relax, and await for approval!

## Check-in!

+ your name here
