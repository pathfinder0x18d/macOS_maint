# Git Tutorial

## Introduction

Git is a distributed version control system used for software development. It allows multiple developers to work on the same codebase simultaneously without conflicting with each other's changes. In this tutorial, we will learn how to use Git for version control.

## Installation

First, you need to install Git on your computer. You can download the latest version of Git from the official Git website.

## Configuration

After installing Git, you need to configure your name and email address using the following commands:

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```
Replace "Your Name" with your actual name, and "youremail@example.com" with your actual email address. This information will be used to identify you as the author of commits in your Git repositories.

## Creating a New Repository

To create a new repository in Git, navigate to the directory where you want to create the repository and run the following command:

```bash
git init
```
This will create a new Git repository in the current directory.

## Staging Changes

After making changes to your files, you need to stage them using the `git add` command. For example, to stage changes. to a file named index.html, run the following command:

```bash
git add index.html
```
This will stage the changes to the index.html file for the next commit.

## Committing Changes

After staging your changes, you need to commit them to your repository using the `git commit` command. For example, to commit your changes with a commit message "Update index.html", run the following command:

```bash
git commit -m "Update index.html"
```
This will commit your changes to your repository with the specified commit message.

## Creating a Remote Repository

To create a remote repository on GitHub, navigate to the GitHub website and click "New repository". Follow the prompts to create a new repository with a name and description.

## Connecting Local Repository to Remote Repository

To connect your local repository to the remote repository on GitHub, run the following command:

```bash
git remote add origin https://github.com/username/repo.git
```
Replace "username" with your GitHub username and "repo" with the name of your repository. This command sets up a connection between your local repository and the remote repository on GitHub.

## Pushing Changes to Remote Repository

To push your changes to the remote repository on GitHub, run the following command:

```css
git push -u origin main
```
Replace "main" with the name of the branch you want to push your changes to. This command will push your committed changes to the remote repository on GitHub.

## Pulling Changes from Remote Repository

If you or someone else has made changes to the remote repository on GitHub, you can pull those changes to your local repository using the `git pull` command. For example, to pull changes from the remote repository on the main branch, run the following command:

```bash
git pull origin main
```
This command will download the changes from the remote repository on GitHub and merge them into your local repository.

## Branching and Merging

Branching allows you to create a new branch that represents a parallel version of your main codebase where you can make and test changes without affecting the main codebase. To create a new branch, you can use the following command:

```bash
git branch branch-name
```
Replace "branch-name" with the name of the new branch. To switch to the new branch, use the following command:

```bash
git checkout branch-name
```
Once you have made changes on the new branch, you can merge them back into the main branch using the following command:

```bash
git merge branch-name
```

## Conclusion

In this tutorial, we have covered the basic Git commands and steps for version control. Git is a powerful tool for collaboration and version control in software development.