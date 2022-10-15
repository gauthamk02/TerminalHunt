# Linux and Git

For this task, you have to follow the instructions below and find the password to *Secret-Scroll.pdf*.

> Note: All the tasks given below should be strictly implemented using Ubuntu terminal commands only.

1. Clone this GitHub repository to your device using 
`git clone https://github.com/gauthamk02/TerminalHunt.git`

2. Create a new directory in the same repository named `solution`.

3. The password has four different parts which will be found in different steps. For the first part solve the below questions and save the answer in a file named `part1.txt` in the `solution` directory.
   - **i.** Multiply the smallest perfect number by **44** 
   - **ii.** Find the Element with atomic mass equal to the previous number.
   - **iii.** Write the atomic number of that element in the file `part1.txt`. 

4. The second part of the password is stored in a file which you need to find by using the below hints.
   - **i.** Find the HCF of **336** and **702** and navigate to that numbered folder. 
   - **ii.** From that, copy the file with the name which is the fourth digit of Pi into the `solution` directory.
   - **iii.** Now rename the file as `part2.txt`.

5. You are halfway there💫, now let's start with a few git commands. Commit the work that you did till now to the `main` branch.
 
6. For the next part of the password, the hint to find it is there in the commit log of the repository. Find the file and copy it to the `solution` directory.

7. The file containing the fourth and last part of the password is present on a different branch😱. Don't worry we’ll help you with this one 😊. Run the command `git branch -a` to see all the local and remote branches of the repository. Type `git checkout <branch_name>` in the terminal to switch to the new branch where <branch_name> is the name of the largest continent. This will create a local copy of that branch and switch to it.

8. Cool, now that you are in the new branch let's find the file 🔍. For that, you can use the command `find . -name <file_name>.txt` where `<file_name>` is the name of the city named after *Godess of War* from Greek mythology. 

9. Since we found the last file let's combine all of them to find the password🥱. But wait, the `solution` directory is in the main branch and it doesn't have the folder with the last file🗿. That's where merging comes in. This branch can be merged with `main` and the folder with the last file will be available on the `main` branch. First, go back to `main` branch using the command `git checkout main` and for merging the branch with the file into `main` use `git merge <branch_name>` where <branch_name> is the name of the branch with the file. Now like before, copy the file `<file-name>.txt` into the solution directory and rename it to `part4.txt`.

10. Finally, all the parts of the password are in one place. Now we just need to combine them to get the password and store it in a new file called `password.txt`. Navigate to the `solutions` folder and concatenate all the contents of the file into a text file called `password.txt`. After concatenating delete all the files except `password.txt`.

11. Congrats🎉, you can now open the protected PDF with the password you found. For the final part of the task, create a *SOLUTION.md* file in your `amfoss-tasks` task directory and write detailed terminal commands which you have used in each step and at last keep the Screenshot image of the PDF. Also, write the Git terminal commands that you will use to push all your work to your `amfoss-tasks` GitHub repository.