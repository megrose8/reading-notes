# Class 3 Notes
## Revisions and the Cloud
*Key Questions* 
+ What is Version Control?
+ What is cloning in Git?
+ What is the command to track and stage files?
+ What is the command to take a snapshot of your changed files?
+ What is the command to send your changed files to Github?  

**Version Control**
+ Local Version Control *(VCS)*: One database on your hard disk, storing continuous changes of files. VCS is at work when one writes code and saves it to *their* computer's file explorer.
+ Centralized Version Control *(CVCS)*: A single server that stores all changes and versions of files, allowing access by various clients and/or teams of developers. The invention of this method of version control allowed for greater ease in collaboration and control over revision privileges.
+ Distributed Version Control *(DVCS)*: Eliminates vulnerability of a single server. DVCS allows mirrored repositories to elimate the risk of lost information due to a single server's failure. The mirroring of repositories further enables use of multiple collaborators on a project.

**Cloning**
 Allows for copying of existing GIT repositories into other locations. Cloning initiates the copying of all versions of all files for a project. `git clone https:// INSERT LINK`

 **Quick Guide to Git Workflow**  
 `Git Add` This command allows the user to name the files that they would like to upload or update to their repository.  
 `Git Commit` Each time you save a changed file, Git creates a snapshot of the filer and stores a reference to it. When in Powershell use `Git Commit -m "DESCRIBE CHANGES"`  
 `Git Status` Allows the user to know how up to date the local file is to the online repository. It will also show the changes to be committed if the user pushes it to Git. It is in this step that the file is now "staged."  
 `Git Push` Is the final command that pushes your committed/staged files onto the online repository, in this case, Git Hub. 

**Quick Guide to Git Flow**
[Alt Text: Diagram of Git Clone and Git Flow](GITFLOW2.jpg)


Reading: 
[Git Tutorial: A Comprehensive Guide](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
In Class Notes: 

