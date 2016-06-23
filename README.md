# DSTK_Course: Data Science Toolkit Course Repo

##FAQ's

###General
*What is a good git tutorial?
 there are a number of git resources. but the gitimmersion.com provides a pretty good tutorial for deep dive learning


###GIT commands
*Windows: I forgot where I created my repo, how do I find it?
	**There is a hidden .git directory
	**On Windows, go to start and type in git
	**Under files you will see the ".git" library
	**Click on it and it should open to your repo location
*What is the status of my git repository?
	$ git status
	On branch master
	Initial commit
	nothing to commit (create/copy files and use "git add" to track)
	kadasani@SEA-1850016271 MINGW64 /c/My Projects/Coursera/DSTK_Course (master)
*What is in the config files?
	**git config --global --list
	**git config --system --list
	**git config --local --list (only works in the local repo directory)
* How do I add new files to source control?
	open gitbash, browse to your repo directory
	**git add <filename>
	**git commit
* How do I sync the local repo with the remote repo?
	
* How do i get both local and remote repo synched up?

* How do I know if there are any outstanding changes in my repo?
	**$git status
	
###Installing R Packages
* Why do I need R Packages?
  Base R system has basic functionality for implementing using the R language. But the additional package help build interactive applications, cleaning data, and analyzing data. R packages are a great way to extend R functionality
* Where can I obtain R packages?
  You can go to the CRAN web site to obtain R packages. there are ~5200 packages on CRAN.
* How can I get a list of available packages on CRAN?
  Open R studio and type the command at the prompt
	a <- available.Packages()
	head(rownames(a), 100) ##will display 100 available packages
* How can I install an R package?
	You can use R Studio Tools menu to isntall packages or run the install.packages function in R. e.g: install.packages(c("slidfy", "devtools" )).
	You have to use the library(<library name>) function to load the library that is installed. Use search() to list the functions in the library that was loaded.
	Here is the output from the installation of devtools
	> library(devtools)
	> search()
	 [1] ".GlobalEnv"        "package:devtools" 
	 [3] "tools:rstudio"     "package:stats"    
	 [5] "package:graphics"  "package:grDevices"
	 [7] "package:utils"     "package:datasets" 
	 [9] "package:methods"   "Autoloads"        
	[11] "package:base"
* 
  
