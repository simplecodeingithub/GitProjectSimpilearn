“Git Final Project for Simplilearn by Chaitra Boregowda”

<h1>Branching Development Model</h1>
<h2>Description</h2>

Create a branching model to help your team understand the Git Feature Branch Workflow for faster and efficient integration of work
 

<h3>Background of the problem statement:</h3>

M-theta Technology Solutions hired you as a DevOps Architect. It is undergoing an infrastructural change to implement DevOps to develop and deliver the products. Since M-theta is an Agile organization, they follow the Scrum methodology to develop the projects incrementally. Hence, the company wants to adopt Git as a Source Code Management (SCM) tool for faster integration of work and smooth transition into DevOps.

So, as a DevOps Architect, you have been asked to build a branching model to demonstrate the Git Feature Branch Workflow for the company’s engineering team. In the branching model, you are required to create a Production branch which will act as the main (master) branch, an Integration branch which will again have two branches inside it namely Feature 1 and Feature 2, and a Hotfix branch which will be used for fixing any issues that could come up from Integration or Production branches.
<h3>You must use the following:</h3>

Git: To build the branching model

 <h2>Steps to perform:</h2>

1.Start with the Production branch (master branch), and then create a HotFix  and Integration branch

2.Subsequently, create Feature 1 and 2 branches that integrate to the Integration branch as shown in the above figure.

3.Commit some changes in the Feature 2 branch and merge it into the Integration branch. Delete this branch once merging is complete.

4.Commit some changes in the Feature 1 branch and rebase it to the Integration branch

5.Merge the Integration branch into Hotfix and Production branch to update these branches

6.Commit some changes in Feature 1 branch, and then merge it into Integration, Hotfix, and Production branch. Delete this branch once merging is complete

7.Commit some changes in the Hotfix branch and merge it into the Production as well as the Integration branch.
