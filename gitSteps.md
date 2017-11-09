# Steps for Project_2 gitHub

### Branches
* Master Branch: 
	/docs (deployed code)
	everything else - the working code

* Personal Branch
	each of us has our own

### On local machine 
* retrieve repository
 	git clone (master branch)

* create your personal branch
 	git branch (your name)

* move into your branch
 	git checkout (your name)

* Make changes and complete tasks


### Before pushing to git
* update master branch
	git checkout master
	git pull origin master

* merge master into personal branch
	git checkout (your name)
	git merge master

* resolve any conflicts (the >>> show differences, the === seperates branches)
	Here are lines that are either unchanged from the common
	ancestor, or cleanly resolved because only one side changed.
	<<<<<<< yours:sample.txt
	Conflict resolution is hard;
	let's go shopping.
	=======
	Git makes conflict resolution easy.
	>>>>>>> theirs:sample.txt
	And here is another line that is cleanly resolved or unmodified.

### Push your changes to gitHub
	git push origin (your name)