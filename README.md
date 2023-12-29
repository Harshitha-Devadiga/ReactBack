# ReactBack
Re learning react
<br>Author- Harshitha Devadiga (HarsH)

Git Hub Gauidlines:
<br>&emsp;
<b>A)When you initially create Git respository & had worked in it,and now you want to clone it with your local device.</b>
          <br>&emsp;&emsp;
1)<b>git clone </b><Repositiry_Link> -> Copies the repository in github to local folder.
          <br>&emsp;&emsp;
2)Now you can do any changes want to do in the repository in local folder.
		<br>&emsp;&emsp;
3)<b>git cd</b> <Repository_Name> ->To get into the repository.
		<br>&emsp;&emsp;
4)i)<b>git add</b> <folder_name> ->The respective folder is ready to commit.
 		<br>&emsp;&emsp;&emsp;
  ii)<b>git add . </b>->All the folders which are modified are ready to commit.
		<br>&emsp;&emsp;
5)<b>git commit -m "<Commit_message>" </b>-> commit the changes in local pc to the repository but this changes are not reflected in the GitHub yet.
		<br>&emsp;&emsp;
6)git push origin main -> Now all changes in the local pc are refelcted in the Original GitHub repesitory once u refresh the page.


<b>B).To see updates made by someone else in a GitHub repository that you have already cloned to your local PC, you can follow these steps</b>:
&emsp;&emsp;
<br>&emsp;&emsp;1.Open a terminal or command prompt on your local machine and navigate to the directory where you cloned the GitHub repository.
<br>&emsp;&emsp;<b>2.git fetch</b> :This command fetches the changes from the remote repository but does not apply them to your local working directory.
<br>&emsp;&emsp;3. Update Your Local Branch:
If you want to update your local working directory to reflect the changes from the remote repository, you need to merge or rebase your local branch. The command you use depends on your preferred workflow:
<br>&emsp;&emsp;i. If you are using a simple feature branch workflow, you can use git merge:
<b>git merge origin/main</b>
<br>&emsp;&emsp;Replace main with the name of the branch you want to update.
<br>&emsp;&emsp;ii. If you are using a more advanced workflow and want to incorporate the changes using rebase, you can use git pull:<b>git pull --rebase</b>
<br>&emsp;&emsp;4.<b> git log </b->This command shows the commit history, including information about the latest commits that were fetched.
