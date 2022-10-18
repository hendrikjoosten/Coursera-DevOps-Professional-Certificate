## Introduction to CI/CD

### what is ci/cd

ci is an automation project that allows you to constantly merge code into the main branch
plan code build test

cd prepares code for deployment (production like environment)
release deploy operate

continuous deployment (deliver to production)

build test is the devops time when ci cd happens

#### benefits
 - faster reaction times to code
 - reduced code integration risk
 - more testing 
 - more code review.

### platform and tools

gitlab
bitbucket
github

Jenkins - central building software
Travis CI - hosted ci service
circle CI - platform for devops
github actions - only works with github.

### what is infrastructure as code

textual file format that can build servers and storage and networks

same environment every time

written in yaml

#### the old toools
Terraform
Ansible
Chef
Puppet - declarative 

#### the new tools


CI consists of the Plan, Code, Build, and Test phases. 

CD consists of the Release, Deploy, and Operate phases. 

# Continuous Integration

## main benefits


# Social Coding


## Jenkins
jenkins file

## CircleCI
yaml

## travis CI
yaml

###Summary & Highlights: Understanding Continuous Integration (CI)

 - CI is an automation process that helps developers continuously integrate code by using short-lived branches. 

 - CI involves frequent pull requests that are easy to review and encourage collaboration. 

 - CI automatically runs code through predefined tests, streamlining development. 

 - With CI/CD, you get: 

 - Faster reaction times to changes 

 - Reduced code integration risk 

 - Higher code quality 

 - Confirmation that the code in version control works 

 - Social coding leads to high-quality code and increased collaboration, saving time, effort, and money. 

 - Git enables DevOps and has many commands that provide essential functionality. 

 - Developers use Git’sFeature Branch Workflow to develop clean, concise, high-quality code. 

 - The Git Feature Branch Workflow involves five steps: 

 - Clone a repository to your local system and create a branch to work on your issue. 

 - Commit changes to that branch. 

 - Push your changes to the remote branch. 

 - Issue a pull request to have your work reviewed. 

 - Merge your code to the main branch and close the issue. 

 - Standard CI tools include but are not limited to Jenkins, CircleCI, TravisCI, and GitHub Actions, and each has advantages and disadvantages. 

 - You can write your CI pipelines as code for your CI tool to run. 

Many CI tools are offered as services that you can easily run and scale on the cloud.


# github actions
You configure GitHub Actions by creating a .github/workflows folder and placing workflow .yaml files in it, workflow components include events, jobs, runners, steps, and actions, an event is something that activates the execution of a workflow, and a job is a set of steps that use the same runner for execution.

