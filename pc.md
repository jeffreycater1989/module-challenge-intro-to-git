## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
2. What is the difference between Git and GitHub?
3. Why do we create a branch?
4. What is the purpose of a Pull Request?
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
7. What is a merge conflict?
8. How do you resolve a merge conflict?

answer 1) Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

answer 2) in simple terms -  Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories

answer 3) We create branches to keep our work separate from the main until we push them together

Answer 4) TO see the differences betweet he main code and the code you are currently working on before merging them together

Answer 5) git checkout

Answer 6)
    - Git Fetch - Download objects and refs from another repository
    - Git Pull - Fetch from and integrate with another repository or a local branch
    - Git Merge -  Join two or more development histories together

Answer 7) a conflict occurs if the current file and the other file have changes in a common segment of lines.

answer 8)
    Step 1) Under your repository name, click  Pull requests.
    
    step 2) In the "Pull Requests" list, click the pull request with a merge conflict that you'd like to resolve.
    
    step 3) Near the bottom of your pull request, click Resolve conflicts.
    
    step 4) Decide if you want to keep only your branch's changes, keep only the other branch's changes, or make a brand new change, which may incorporate changes from both branches. Delete the conflict markers <<<<<<<, =======, >>>>>>> and make the changes you want in the final merge.
    
    step 5) If you have more than one merge conflict in your file, scroll down to the next set of conflict markers and repeat steps four and five to resolve your merge conflict.
    
    Step 6) Once you've resolved all the conflicts in the file, click Mark as resolved.
    
    Step 7) If you have more than one file with a conflict, select the next file you want to edit on the left side of the page under "conflicting files" and repeat steps four through seven until you've resolved all of your pull request's merge conflicts.
    
    step 8) Once you've resolved all your merge conflicts, click Commit merge. This merges the entire base branch into your head branch.
    
    step 9) If prompted, review the branch that you are committing to.
    
        If the head branch is the default branch of the repository, you can choose either to update this branch with the changes you made to resolve the conflict, or to create a new branch and use this as the head branch of the pull request.

        If you choose to create a new branch, enter a name for the branch.
    
        If the head branch of your pull request is protected you must create a new branch. You won't get the option to update the protected branch.
    
        Click Create branch and update my pull request or I understand, continue updating BRANCH. The button text corresponds to the action you are performing.

    Step 10) To merge your pull request, click Merge pull request. For more information about other pull request merge options  

    brian made do this!