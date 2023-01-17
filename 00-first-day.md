# 00 - week 1 git flow

Each week we will push up lessons and solutions. We want you to keep all of the code on your own git branch.

## SSH KEYS

1. Add `ssh keys` to GitLab and GitHub. Please regenerate the ssh keys without a passphrase. 

## DIRECTORY STRUCTURE SET UP

Here’s the set up you do only in week 1:

1. Create folder structure

    a. `mkdir bootcamp`

    b. `cd bootcamp`

    c. `mkdir playground`

    d. `mkdir homework`

    e. clone curriculum  - `git clone [git@nu.bootcampcontent.com](mailto:git@nu.bootcampcontent.com):NU-Coding-Bootcamp/NU-VIRT-FSF-PT-01-2023-U-LOLC.git`
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c1f35f15-6801-4f90-9b1d-384de9fa6278/Untitled.png)
    

## CREATE YOUR WORKING GIT BRANCH (only once)

1. cd `NU-VIRT-FSF-PT-01-2023-U-LOLC`you will be on a branch called `main`. If the branch you are on is not `main`, checkout to main, `git checkout main`. This means that `main` branch already exists. 

2. `git pull` - this will fetch code that is in the GitLab cloud.

3. Create a branch where you will keep all your classtime work - `git checkout -b <branch name>`. Notice the `-b`. This means you are creating a new branch.
    a. Example: `git checkout -b class-content`

4. At the end of class add your work to the class-content branch

    a. `git add -A`

    b. `git commit -m "week 1 exercises"` - What you put in the quotes explains what work you completed”

## WEEKLY PULLING CURRICULUM

**Here’s the process:**

1. cd `NU-VIRT-FSF-PT-01-2023-U-LOLC`
2. checkout to branch `main`

    a. `git checkout main`

    b. `git pull`- you will get all the current curriculum and solutions. `main` will be updated.

    c. `git checkout class-content` -  check out to your class branch

    d. `git merge main`- merge the content that is on `main` with your branch.

    e. at the end of class while on your class-content branch, `git add -A` (add all the changes)

    f. `git commit -m "week {num} exercises"` - What you put in the quotes explains what work you completed”