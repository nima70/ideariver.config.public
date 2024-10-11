# Ideariver.config
## Introduction
This repository contains language-agnostic configuration files that are used across the Ideariver ecosystem.

## Features
- Event Management
Includes configuration files related to event handling and management across different platforms.

## License
This project is licensed under the MIT License.


# Adding ideariver.config as a Git Submodule

This repository can be added as a submodule to your existing project. Follow the steps below to integrate it into your project.

## Step-by-Step Instructions

1. **Navigate to your project directory**:
   Open your terminal or PowerShell and navigate to the root directory of your project where you want to add this submodule.

```bash
   cd path_to_your_project_directory
```
## Add the submodule:
Run the following command to add this repository as a submodule under the desired directory:

```bash
git submodule add https://github.com/nima70/ideariver.config.public.git path_to_submodule_directory
```
Replace path_to_submodule_directory with the directory where you want the submodule to reside (e.g., config/ideariver.config).

## Initialize the submodule: 
After adding the submodule, initialize it by running:

```bash
git submodule init
```
## Update the submodule: 
To fetch the latest code from the submodule repository, use:

```bash
git submodule update
```

## Cloning the Project with Submodules:
If you're cloning the main project and it contains submodules, clone it with the --recurse-submodules flag to initialize and fetch submodules in one step:

```bash

git clone --recurse-submodules https://github.com/your-main-project.git
```
If you forget to use the --recurse-submodules flag, you can initialize and update the submodules manually with:

```bash
git submodule update --init --recursive
```