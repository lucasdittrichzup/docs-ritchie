---
title: Basic 2
weight: 86
description: 'In this section, you will find a step by step to use credentials on Ritchie.'
---

# Basic 2: Credentials

## Objective

Create a formula on Ritchie that will **return a JSON with Github credentials**.

> **Note**: The tutorial is to configure those inputs inside the **config.json** file, but run the formula without informing them as `prompt` or `stdin` \(they will be extracted automatically\). You'll find all the informations you need in the [**how to manipulate credentials**](/docs-ritchie/credentials/set-credentials/) tutorial section.

{{% alert color="info" %}}
Command suggestion: **`rit github get user`**
{{% /alert %}}

## Inputs

This formula needs to contain \(at least\) those two inputs parameters:

* Username \(`RIT_GIT_USER`\). 
* Token \( `RIT_GIT_TOKEN`\).

## Step by step

The formula needs to follow the next steps:

1. Extract all inputs parameters. 
2. Consume the [**GitHub api**](https://docs.github.com/en/free-pro-team@latest/rest/reference/users#get-a-user) to get the user data. 
3. Return the result on the terminal.

## Improvement suggestions

 If you want to play a little more, here are some suggestions:

* Develop some Github operation by manipulating these credentials. 
* Code a formula which will allow the user to create a repository on Github. 
* Code a formula which will allow the user to **add**, **commit** and **push** using only one command.  
* Code a formula which will allow the user to generate a release of the informed Github repository.

## **Next steps** 

👉 If you've completed the second tutorial, let's go to the [**intermediate task**](/docs-ritchie/tutorials/intermediate/)!