# CMPG-323-Overview-23523778
CMPG 323 Semester project overview

## Repositories
![RepoOverview](https://user-images.githubusercontent.com/68903153/185241730-39007c88-da87-4e3a-9ca4-331c00e994b1.png)

Project 1 Overview: This project serves as an overview to implement source control through git.
The entire semester project will be split up into 5 sub-projects within an agile scrum environment.
Each project will have it's own repository and all of them will link together into a central overview project,
with repository: CMPG-323-Overview-23523778

* Project 1 repository: CMPG-323-Overview-23523778
  * https://github.com/JMX969/CMPG-323-Overview-23523778.git
* Project 2 repository: CMPG-323-project2-23523778
  * https://github.com/JMX969/Project-323-Project2-23523778.git
* Project 3 repository: CMPG-323-project3-23523778
* Project 4 repository: CMPG-323-project4-23523778
* Project 5 repository: CMPG-323-project5-23523778

## Branching Strategies
Project 1: Branch setup-project: This branch will be used to configurate, setup and update README.md.
This branch will then commit and merge with main branch

Project 2 to 5: Branch development-branch: This branch will be used to work on all the different features for the required project.
The development-branch can then be used by multiple different developers to work on multiple features at the same time.
After finishing a feature, the developer can then commit and merge the development branch with another branch called operational-branch.
operational-branch: is used to test each of the completed features of code cohesively together as a whole. This branch serves as the "testing branch"
before merging with main. This is to ensure the integrity and stability of a functional working main.

## .gitignore Files
Currently in project 1 there are no .gitignor files being used, but for future projects the .suo file can be ignored when commiting changes to a branch.
This will ultimately help reduce some of the merging conflicts into main, especially if there are multiple developers merging changes into the main branch.

## Storage of credentials and sensitive information
Creditials of each contributer/developer can be captured and configurated seperatedly for each development-branch used for contribution.

## References
* Project 1:
 * Example of Board View: https://github.com/users/JacquiM/projects/16
 * GitHub Repository Documentation: https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories
 * GitHub Project Documentation: https://docs.github.com/en/issues/trying-out-the-new-projects-experience/about-projects
 * Manage the Lifecycle of your projects on GitHub: https://docs.microsoft.com/en-us/learn/paths/manage-project-lifecycle-github/
 * What is a Burndown Chart: https://www.visual-paradigm.com/scrum/scrum-burndown-chart/
 * Introduction to Git: https://docs.microsoft.com/en-us/learn/modules/intro-to-git/
