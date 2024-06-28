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

>>Q3 how to list tags ?
        
        git tag

>> Q4 how to delete tag locally and remotely ?

    localy 
        
        git tag -d "tag name"

    remotly

        git push origin --delete "tag name"

>> add image to readme file

     

     <img src="https://tse1.mm.bing.net/th?id=OIP.RgQ2nbSMrzEfBlEjDT3hmwHaFh&pid=Api&P=0&h=220" alt="img">
     