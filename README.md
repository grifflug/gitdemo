# Git Notes
Scott Chacon

# References
* http://gitref.org
* http://progit.org

# Commands
* git clone https://github.com/grifflug/gitdemo.git  // pull + setup
* git init                              // starts new .git
* git pull origin master                // fetch + merge
* git fetch origin master               // pull not merge
* git remote 	 	     // show remotes
* git remote remove origin              // removes origin (which is an alias for the git server)
* git remote add theHub https://github.com/gitdemo // add theHub (alias)
* git add -p file	    	     // add changes one at a time
* git add .  		     // add all
* git reset			     // undo git add
* git commit -am 'Lazy'	                // commit + add all
* git push origin master	     // replace origin's master with your current branch
* git branch     	    	     // show branches
* git branch blue 	                // create branch blue at head
* git checkout red 	                // switch to red branch (move head to red)
* git checkout -b maroon red            // create branch maroon at red and switch to maroon
* git merge blue 	       	     // merge blue with current branch, then move head to newly merged version
* git log -p 		     // show patch
* git log --stat		     // something to do with stats
* git log jMaster ^rMaster              // Everything unique to Josh's master compared to Rob's master

# Config
* git config --global color.ui true
* git config --global alias.lol "log --oneline --graph --decorate"
* git config --global alias.st "status -s" 		                  // simple one line
* git config --global alias.cam “commit -am”		                  // Commit all w/ message

# Bash tools
Q: How did he get [~/ (master)] as his bash prompt?
