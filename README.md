#Lab 2

>> Q1 Removing Branches Locally and Remotely

    To delete a local branch:

        git branch -d branch_name

    If the branch has unmerged changes and you want to force delete

        git branch -D branch_name


    To delete a remote branch:

        git push origin --delete branch_name

>>Q2 CheckOut Another Branch Without Committing Changes

    Stash Your Changes

        git stash
        
        git checkout branch_name
        
        git stash pop