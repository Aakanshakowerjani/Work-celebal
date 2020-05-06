# Development

### Configuring Github
 - Create an account on Github.
 - Create a new Repository and copy its url.
 - Install git locally using Command Prompt.
 - Move to directory where your project files are.
 - Clone local repository using following command where link is copied link of your repository:
```sh 
     git clone link
```
 - Change directory to that folder.

### Adding File to Github
 -   Add the project file github .
 -   Commiting the file following with message.
 -   Finally pushing the file to github repo.
 ```sh
     git add filename.ext
     git commit -m "message"
     git push
 ```
 - Go to github repository page and refresh it following changes will reflect.

### Updating the existing file 

  - Pull the project file from github to your local repository :
 ```sh
     git pull
 ```
  - Update the file and push it back to the github by the above adding commands.

### Testing the updated file

  - Testing is done to check whether the actual results match the expected results. It also helps to identify errors, gaps or missing requirements in contrary to the actual requirements.It can be either done manually or using automated tools.

### Frameworks for Testing in python

|Framework|License|part of|Category|Category Special feature|
|---------|-------|-------|--------|------------------------|
|Robot|Free software(ASF License)|Python generic test libraries.|Acceptance Testing|Keyword-driven testing approach.|
|Pytest|Free Software(MIT License)|Stand alone, allows compact test suites.|Unit Testing|Special and simple class fixture for making testing easier.
|
|unittest|Free software (MIT License)|Part of Python standard library.|Unit Testing|Fast test collection and flexible test execution.|
|DocTest|Free software (MIT License)|Part of Python standard library.|Unit Testing|Python Interactive Shell for the command prompt and inclusive application.|
|Nose2|Free software(BSD License)|Carries unittest features with additional feature and plugins.|unittest extension|A large number of plugins.|
|Testify|Free software(ASF License)|Carries unittest and nose features with additional feature and plugins.|unittest extension|Test discovery enhancement.|

(Abbreviations: MIT = Massachusetts Institute of Technology (1980), BSD = Berkeley Software Distribution (1988), ASF = Apache Software Foundation(2004))

### Merge Conflict 
A merge conflict is an event that occurs when Git is unable to automatically resolve differences in code between two commits.When all the changes in the code occur on different lines or in different files, Git will successfully merge commits without your help. However, when there are conflicting changes on the same lines, a “merge conflict” occurs because Git doesn’t know which code to keep and which to discard.

### Resolving Merge Conflict
 - This is resolve manually.
 - Remove all head and tail and make project as per your requirements.
 - Remove all <<<<<, ====== and >>>>>> and write desirable code.
 - Then push that file again to github.
 
### Git log
 - You can view all the changes you made to your repo by following commands:
```sh
     git log
```
### Git Reset
 - Consider a situation where you made the change to the code and you no longer feel like keeping the change you can always go back to the previous version of the code by the following command:
```sh
     git reset --hard<commit hash value>
```
