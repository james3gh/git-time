Hey !!! <br/>
James this side , 2nd yr student from IITBHU <br/>
My git repo <a href = "https://github.com/james3gh/go-git-jt">Link</a> <br/>
To know more, <a href = "https://github.com/james3gh">click here</a>.

**Ques** - What do you really understand from SSH keys? What are the advantages of using it ? /This is garbage text/

**Ans** - It is medium through which a local server can send/receive data to a remote server in a secure manner. SSH has a public and private key.

- Data is encrypted (specially username and password is secured)
- File transfer is much safer.
- Through SSH key it doesn't require to enter usrnme and passwrd everytime we clone our repo.

<br />

**Ques** - How to edit the last commit message in git?

**Ans** - To edit the last commit the user has made, use this command <br />
git commit --amend -m "title" -m "description" . <br />
You can also write the commit message in vi editor using amend command.
However using this command makes a new commit hash, so one need to force push it to be reflected in remote repo.

### Ques-1 How and why merge conflicts arise?

**Ans-1** According to me, merge conflicts arise when two different changes on the same line occurs in a file. Eg. merging 2 branches. However git cannot solve it automatically, thus its the work of the developer to consider which changes he likes to keep.

### Ques-2 Is force push a good practice? Yes/No why? In most of the tasks on this repo, you used force push, so why this practice is Okay (neither good nor bad) in your case?

**Ans-2** Force push is not a good practice though as it changes the git commit history. The other contributors working on a project can face issue due to this. The more better habit is to revert commits, so that all developers are awared about it.

In our case, as working on the individual named files, doesn't make any change to the files of other contributors. However while working on some common issues/files can cause the bugs, if someone forced pushed his/her changes.

### Ques-3 Name anyone Git or Github topic on which any issue is not made on this repo. (Your answer should be different from others.

**Ans-3** Working on some issue that uses some concept of detached head if added can be really helpful

Git objects explained.
refs explained
objects stores commits

q git tree and blob
tree explained

blob explained

Reordering commits makes a clearer and understandable git history. It makes the developer understand their code changes in a uniform and time-based manner.

Git submodules is like a git repository inside another git repo. Changes made in submodules are not tracked by main repo. It is useful to have some separate projects inside a git repo if the projects is much complex. This make the projects divide into small modules to work upon.
