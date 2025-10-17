# Git-commands
Git commands

 1. `Git Init --> To Initialize a git repository`

 2. `git add filename`

    To track the file

3. `git status`

    To check all the untracked files and status

4. `.git` --> this stores metadata of local repositories.

5.  `git log`

     This command will display the comitted files information along with Id's

6. `git show File-id`

    this command will show the comitted information along with timestamp.

7. `git diff file-name`

   This command will dispay the modifications made in the file and it will work before the file is moved to stagging(git add cmd)

8. `git diff --cached file-name`

   This command is used to check the modifications made to file after pushed to stagging before commit

9. `git log --oneline`

    This command will display the logs information in shorter form

10. `.gitignore`

    Ex: vm .gitignore

        The above file is created where you can add files that you want to ignore during stagging.
        file1.txt, file2.txt

11. `git commit --amend -m"Your amended commit message"`

     you can only amend of recent commit only


########################################################### **Git Tags** ###################################################

1. `git tag -a <tagname> <commit id> -m"Message"`

   Ex: git tag -a v1.0 775504 -m"First version v1.0"

2. `git tag -l` ---> to list all the tags

3. `git show <tagname>`

   This tag to show the modifications made during that commit in the code

4. `git tag -d <tag-name>`

   THis command is used to delete the tag that is created

   



    

    



   

  

     
