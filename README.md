GIT OPERATIONS JUN 17 Onward

HOW TO USE GIT 

1) From Scrach (creting new repo)

	step 1. Start your project by creating new directory with mkdir and swiched to it by cd /
	step 2. run git init 
	step 3. create new files/folders or start your project
	step 4. ADD them with -> git add * 	//add all at a time 
				 git add file 	//for specific

	step 5. commit with   -> git commit -m "First commit"
	step 6. Goto github .
	step 7. Create new repo
	step 8. git remote add origin git@github.com:DAVijay/git.git
	step 8. git push -u origin master

    		Sometimes u may get some error like 
			Permission denied (publickey).
			fatal: Could not read from remote repository.

			Please make sure you have the correct access rights
			and the repository exists. 
		then add this to remote :- 
			git remote set-url origin https://github.com/DAVijay/git.git
			git remote set-url origin https://github.com/DAVijay/git.git

	VOILA, YOU DONE IT!!!!!

2) From existing.
	
	just clone it to your local computer and do same operation as above.
