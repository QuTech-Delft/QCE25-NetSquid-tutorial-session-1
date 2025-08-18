# QCE25 NetSquid Tutorial - Session 1

This repository contains the materials for the QCE25 NetSquid tutorial session, specifically:

- Tutorial notebooks
- Exercise
- Exercise solution

## Getting Started

### Installation

**Prerequisites:**
This tutorial requires the installation of the NetSquid Python package. This requires you to create an account on the NetSquid forum.
If you do not have a NetSquid forum account, first create one: https://forum.netsquid.org/ucp.php?mode=register

**Environment Setup:**
Set your NetSquid account credentials as environment variables by executing the following commands with your actual username and password:
```bash
export NETSQUIDPYPI_USER=your_username
export NETSQUIDPYPI_PWD=your_password
```

**Install Dependencies:**
Next, install all required dependencies for this tutorial, including NetSquid, by running:
```bash
make install
```

### Running the Tutorial
Launch the Jupyter Notebook environment:
```bash
jupyter notebook
```