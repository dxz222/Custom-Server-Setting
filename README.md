# STEM Serve Setting
## Introduction
This repository contains the codes for multi-batch running on server. 

## Dependency
- screen

## Usage
1. Copy the file `__sbatch.sh` into your home directory.
2. Copy the code inside `more_than_bashrc.sh` at the end of your `.bashrc` file. Care about that do not change the original code in your `.bashrc` file.
3. You could submit mission

## Alert
These codes are used for the server without sbatch plug-in installed. If you are using a cluster or server with sbatch plug-in, these codes will be incompatible with it thus cause some errors.
