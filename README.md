GIT CHEAT SHEET 
====

**CREATE REPOSITORIES**  
Start a new repository or obtain one from an existing URL

> **`$ git init [project-name]`**  
*Creates a new local repository with the specified name*

> **`$ git clone [url]`**  
*Downloads a project and its entire version history*  

---

**MAKE CHANGES**  
Review edits and craf a commit transaction

> **`$ git status`**  
*Lists all new or modified files to be commited*

> **`$ git add [file]`**  
*Snapshots the file in preparation for versioning*

> **`$ git reset [file]`**  
*Unstages the file, but preserve its contents*

> **`$ git diff`**  
*Shows file differences not yet staged*

> **`$ git diff --staged`**  
*Shows file differences between staging and the last file version*

> **`$ git commit -m "[descriptive message]"`**  
*Records file snapshots permanently in version history*
