# data-analytics.internship.cmc
Data analytics exercise for CMC Data Engineering 

Welcome to the CMC Data Engineering internship tech exercise. We hope you'll enjoy it as much as we did creating it for you! Before you begin, please bare in mind our main focus is evaluating how you try to solve the exercises below. Although it's required that you show programming skills, you're also encouraged to complete/give your answers however you see fit, say an explanation instead of a chunk of code.

Wishing you the best of lucks, please take your time to complete the exercises below.

# E1 Setup and Development Operations

The exercises below requires that you begin by setting up a development environment. Start by forking this repository. Your answers to the exercises below are to be pushed to your fork. When finished, you can submit the answers by issuing a pull request to the `dev` branch of this repository. Please include your name in the pull request title, not everybody knows the true identity of `citizenfive`!

Each exercise should be pushed to different branches of `dev` named as `E1`, `E2`, ... When finished, merge your branches to dev and issue a pull request from your fork to the `dev` branch of this repo. We'll be having a look at your fork later on to observe how you structure your commits, hope you don't mind our prying...

You're asked to use a python framework to solve the exercises below. Please edit this file to include an explanation of how to setup the environment to run your solution. Having received your pull request, we'll pull your changes and follow your instructions to run your code. You can also choose to include a script that automates the installation of your setup in a linux based distro, say ubuntu (Please don't make us run something on the lines of Arch!)

**Note** You're free to come up with whatever setup, from a raspberrypi server, to a local jupyter installation, to a modern cloud architecture and deployment pipelines, but keeping it simple should be more than sufficient :)

# E2 Data Analysis

You'll be creating simple data structures about Anna, Alex, Frederic and Peter. You'll find data about these four under `public/`.

# E21 Display a table of friendship between Anna, Alex, Frederic and Peter

The columns are named as ``anna``, ``alex``, ``frederic`` and ``peter``, of type `Boolean`. The indexes are: ``anna``, ``alex``, ``frederic`` and ``peter``.

||anna|alex|frederic|peter|
|---|---|---|---|---|
|anna|True|True|False|True|
|alex|True|True|True|False|
|frederic|False|True|True|False|
|peter|True|False|False|True|

# E22 Display the ages and birth dates for Anna, Alex, Frederic and Peter

Peter's age is given in unix timestamp. The birthdate column must be of the Date data type. The multi-index must be the name and the age

|||birthdate|
|---|---|---|
|anna|32|30/06/1989|
|alex|19|13/12/1992|
|frederic|21|01/01/1990|
|peter|16|04/05/1995|# 

# E23 Display the sum of ages between each group of friends:
+ G1 Anna, Alex
+ G2 Anna, Peter
+ G3 Frederic, Alex  
No need to auto-generate groups of friends. The index must be: 0, 1, 2.

||group|sum of ages|mean|
|---|---|---|---|
|0|G1|51|25.2|
|1|G2|48|24|
|2|G3|40|20|

