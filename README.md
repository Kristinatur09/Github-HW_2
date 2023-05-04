# Github-HW_2
## In this homework, we learned how to create branches, merge in main, and create a pull request
## $${\color{Teal}Let's\space take\space a\space look\space at\space the\space complete\space flow\space from\space the\space branch\space creation\space to\space pull\space request}$$

1. First, let's create new branches:

   **a) git branch Bag_Reports**
 
   **b) git branch CheckLists**
 
2. Push all branches to an remote repository:

   **git push origin --all**
   
3. make a text document with the bug report structure in the Bag Reports branch:

   **a) git checkout Bag_Reports**
   
   **b) touch Bag_Reports.txt** 
   
   **c) vim Bag_Reports.txt**
   
4. Push the bug report structure to the external repository -

   **a) git add .**
   
   **b) git commit -m "add file Bag_Report"**
   
   **c) git push**
   
5. Merge the Bag Reports branch into Main -

   **a) git checkout main**
   
   **b) git merge Bag_Reports**
   
6. Push main branch to the remote repository - **git push**

7. In the CheckLists branch, outline the checklist structure - 

    **a) git checkout CheckLists**
    
    **b) touch check_list.txt** 
    
    **c) vim check_list.txt**
    
8. Push the structure to the external repository -

   **a) git add .**
   
   **b) git commit - m "add file"**
   
   **c) git push**
   
9. On the remote repository, make a Pull Request of the CheckLists branch in main -

   **a) click the button [Compare&pull request] on the remote repository**
   
   **b) click the button [create pull request]**
   
   **c) add comment**
   
   **d) click the button [merge pull request]**
   
   **e) click the button [confirm merge]**
   
10. Synchronize Remote and Local branches Main - **git pull**  
