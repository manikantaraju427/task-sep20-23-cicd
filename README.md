###  Task Allocation with Jenkins and CI/CD Pipelines ###


### Task 1: Creating a New Task or User Story ###

* Navigate to the GitHub Issues section of my repository.
 
 * Click on the "New Issue" button.
 
 * Provided issue title
 
 * In the issue description, include details relevant information.  saved the issue

 ### Task 2: Assigning the Task to a Developer ###
 
 #Assign labels and assignees as needed to  assign the task.
 (In this case iam solo contributor this projecr iam assigned my self)

 * comments section to communicated specific requirements

### Task 3: Integrating the Feature into the CI/CD Pipeline ###

#Created a new branch for the feature using Git.
   
$git checkout -b feature/new-feature-name

$git add .

$git commit -m "Implemented feature: new-feature-name"

$git push origin feature/new-feature-name

# Access the Jenkins server and configure the Jenkins pipeline for the new feature #

# login jenkins web server 

#Created Jenkins project/job : feature-practice-branch

* In the "Source Code Management" section, specified the GitHub repository URL.

*  In the "Branches to build" field, given my specific branch name   (*/feature/user-registration)

*  saved the project

*  build the project successfully

  ### monitored the build process through the Jenkins console output and confirmed that it finished successfully  ###



### NOTE ###
in this case i dont take any source code and any base application file   


  



