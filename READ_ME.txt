GOOGLE CLASSROOM LINK
https://docs.google.com/document/d/133BZ52XxhlqTtgjUjnWvsawBE2iTYV0Kg9L6cWn4aVQ/edit

GIT DOCUMENTATION
https://git-scm.com/book/en/v2

EXERCISE 1
Interactive Tutorial:
	https://www.katacoda.com/courses/git ←complete scenario 6

EXERCISE 2
Using the PizzaAlgo repo from earlier:
In the Command prompt / Terminal:

1. Create a new branch named test → git branch test
2. git status - to see if I have any changes 
3. Switch to test branch with → git checkout test
4. do some work on test branch and save → add a step 1a for example
5. git status - and see that I have modified Algo file in the test branch
6. git add . - add those changes to the staging areas for test branch
7. git commit -m "reworded a step" - committed those changes to test branch
8. git push origin test - pushed test branch to the remote repository (GitHub)
9. git checkout master - switch to master branch
10. git merge test - merge the changes in test branch to the master branch