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

the job component of a GitHub Actions workflow contains runners, services, steps, and actions, a runner is a server that performs a job on a specific operating system or platform, services are defined as Docker containers, steps are tasks comprising one or more shell commands or actions, actions are procedures that can be executed within a step, and the GitHub Actions Marketplace has many prebuilt actions for you to use in your workflows.

runners 

steps

actions

# Continuous Delivery CD

 CI/CD is not one thing, it’s two separate and distinct things that happen after each other, 
 Continuous Delivery is taking integrated code and deploying it somewhere, 
 
 Continuous Delivery is a software development discipline where you build software in such a way that

  - the software can be released to production at any time, 
  - the reason you have pull requests and feature branches is so you can ensure code changes work before you merge them back into the main branch, and 
  - your code will typically need to go through several stages of Quality Assurance and Staging or Testing to ensure that what you deliver to production is bug-free and fit for purpose.

## CD Tools
 - jenkins
 - spinnaker
 - concourse
 - gitlab
 - travis ci (not feature rich)
 - tekton (kubernetes and OS)
 - Go CD yaml or json 
 - Argo CD

feature, compatibility, ease of use and setup, maintenance 
in your pipeline you need:
 - security
 - vuln scanning
 - secret scanning
 - SAST
 - DAST
 - facilitate code deployement

### Argo cd
declerative, gitops as kubernetes controller

### Tekton
flexible and os
portable
integrates well

### notesCongratulations! You have completed this lesson. At this point in the course, you know: 

Continuous Delivery (CD) is a software development practice that automatically delivers code changes to a production-like environment to ensure that the updated software is ready for release. 

CD has many benefits including reduced deployment time, reduced costs, and scaling based on project size. 

CD has five key principles: 

You need to build in quality. 

You should work in small batches. 

People should solve problems, not perform repetitive tasks. 

You should relentlessly pursue continuous improvement. 

Everyone is responsible for their part in the story. 

Best practices for CD include, but are not limited to, making every change releasable, automating as many processes as possible, and ensuring no application downtime. 

A CI/CD pipeline requires a code repository, build server, integration server, and storage repository. 

Continuous Deployment is a practice that automatically deploys code from the preproduction environment to production. 

Your CD tool should be feature-rich, easy to use, highly compatible, and low maintenance. 

Tools within your CD pipeline should handle scanning and deployment tasks


# Tekton


