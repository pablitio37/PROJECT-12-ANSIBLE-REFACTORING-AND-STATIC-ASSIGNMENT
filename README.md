# PROJECT-12-ANSIBLE-REFACTORING-AND-STATIC-ASSIGNMENT
ANSIBLE REFACTORING AND STATIC ASSIGNMENTS (IMPORTS AND ROLES)

Step 1 – Jenkins job enhancement
Before we begin, let us make some changes to our Jenkins job – now every new change in the codes creates a separate directory which is not very convenient when we want to run some commands from one place. Besides, it consumes space on Jenkins serves with each subsequent change. Let us enhance it by introducing a new Jenkins project/job – we will require Copy Artifact plugin.

Go to your Jenkins-Ansible server and create a new directory called ansible-config-artifact – we will store there all artifacts after each build.

![text1](https://user-images.githubusercontent.com/108102087/208252118-2f7ccba4-e2a8-4423-921f-7593718fac47.PNG)

Create a new Freestyle project (you have done it in Project 9) and name it save_artifact.

![text2](https://user-images.githubusercontent.com/108102087/208262347-6fc34f45-97c9-4cd9-b5b9-8900325ad42b.PNG)

## REFACTOR ANSIBLE CODE BY IMPORTING OTHER PLAYBOOKS INTO SITE.YML

Step 2 – Refactor Ansible code by importing other playbooks into site.yml
Before starting to refactor the codes, ensure that you have pulled down the latest code from master (main) branch, and created a new branch, name it refactor.

new change

another change

yet another change