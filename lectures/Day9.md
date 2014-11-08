Discussed steps and commands for Git
Git init: 
		means to make git care about what is about to happen
git clone: 
		is adding the files to your (physical) computer
git add: 
		Git is aware of the files and should list what it's able to add.
		Make sure you add the file exactly as is.
		For example: if it has Day1.md, write git add Day1.md

git commit: 
			Once you have added this files: git add , you need to commit these changes.
			Git commit -m "". Add a message within the ""
			If this message displayed: no changes added to commit
			You must git add [the file] then commit 

git checkout -b:
			Git checkout is when you want to create a new branch and switch to that branch.
			For example, I want to create a new branch named hello, I'd write git checkout -b hello
			Then it should tell you that you are on branch hello

git checkout [branch] : 
						Git checkout means that you are switches branches. 
						For example, I am on branch hello and now I want to switch to the master branch.
						I would write git checkout master

git remote:
			Shows which nicknames of the remote repositories that you are connected to.
			For example, git remote might display: debugsociety
													origin

git remote -v:
				shows you the entire link of the repositories 
				For example,   
						debugsociety   https://github.com/debugsociety/Curriculum.git (fetch)
						debugsociety   https://github.com/debugsociety/Curriculum.git (push)
						origin    https://github.com/..[yourgithub]/Curriculum.git (fetch)
						origin    https://github.com/..[yourgithub]/Curriculum.git (fetch)
git remote add [url]:
				If you want to add a repository onto your computer
				For example:
						git remote add https://github.com/debugsociety/Curriculum.git

git branch:
			Shows you all the branches on your computer with an asterisk next to the branch you are on.
			For example,
				 master
				*branch2

git push [name of repository] [branch you are pushing]:
												 Git push is when you want to send it to the online repository 
												 Git push is sending the entire branch 
												 For example,
												 			git push debugsociety branch2 

git pull : 
			Git pull means that you are extracting any new changes into your branch
			When you git pull, much be in the correct branch that you want to pull into
			For example, if I want to pull from debugsociety into my branch2
			git pull debugsociety branch2

git merge:
		 Git merge is when you want to update the file
		 For example




