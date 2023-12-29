# ReactBack
Re learning react
<br>Author- Harshitha Devadiga (HarsH)

Git Hub Gauidlines:
<br>&emsp;
A)When you initially create Git respository & had worked in it,and now you want to clone it with your local device.
          <br>&emsp;&emsp;
1)git clone <Repositiry_Link> -> Copies the repository in github to local folder.
          <br>&emsp;&emsp;
2)Now you can do any changes want to do in the repository in local folder.
		<br>&emsp;&emsp;
3)git cd <Repository_Name> ->To get into the repository.
		<br>&emsp;&emsp;
4)i)git add <folder_name> ->The respective folder is ready to commit.
 		<br>&emsp;&emsp;&emsp;
  ii)git add . ->All the folders which are modified are ready to commit.
		<br>&emsp;&emsp;
5)git commit -m "<Commit_message>" -> commit the changes in local pc to the repository but this changes are not reflected in the GitHub yet.
		<br>&emsp;&emsp;
6)git push origin main -> Now all changes in the local pc are refelcted in the Original GitHub repesitory once u refresh the page.


<b>B).To see updates made by someone else in a GitHub repository that you have already cloned to your local PC, you can follow these steps<b>:
&emsp;&emsp;
Navigate to the Local Repository:
<br>1.Open a terminal or command prompt on your local machine and navigate to the directory where you cloned the GitHub repository.<br>

<br>2.git fetch :This command fetches the changes from the remote repository but does not apply them to your local working directory.</br>

<br>3. Update Your Local Branch:
If you want to update your local working directory to reflect the changes from the remote repository, you need to merge or rebase your local branch. The command you use depends on your preferred workflow:<br>

<br>i. If you are using a simple feature branch workflow, you can use git merge:
<b>git merge origin/main<b>
Replace main with the name of the branch you want to update.</br>

<br>ii. If you are using a more advanced workflow and want to incorporate the changes using rebase, you can use git pull:</br>
<br><b>git pull --rebase
This fetches the changes and rebases your local changes on top of the remote changes.</b><br>

<br>4. git log ->This command shows the commit history, including information about the latest commits that were fetched.</br>
