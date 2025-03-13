# Team Development Standards & Best Practices

Welcome to the **Team Development Standards & Best Practices** repository. This document outlines the conventions, workflows, and best practices for our team when working with different tools and languages. Our goal is to promote consistency, maintainability, and efficiency in our projects.

---

## 📌 Table of Contents
- [Team Development Standards \& Best Practices](#team-development-standards--best-practices)
  - [📌 Table of Contents](#-table-of-contents)
  - [0️⃣ General Guidelines](#0️⃣-general-guidelines)
  - [1️⃣ Git Workflow \& Version Control](#1️⃣-git-workflow--version-control)
    - [About the `main` Branch](#about-the-main-branch)
    - [Branch Naming Conventions](#branch-naming-conventions)
      - [From the `main` Branch](#from-the-main-branch)
      - [From Other Branches](#from-other-branches)

---

## 0️⃣ General Guidelines

In this convention, each developer will be identified by an alias. The alias consists of two characters following the pattern `[a-z][a-z0-9]`. 

For example, the developer `John Doe` might choose the alias `jd`, while `Harry Houdini` could select `h2`.

## 1️⃣ Git Workflow & Version Control

### About the `main` Branch

The `main` branch is the default branch for all repositories and should always contain the *latest stable* version of the project. 

If you are the sole developer on a project, you may use the `main` branch for development. However, if multiple developers are collaborating, it is recommended to create separate branches for each feature or bug fix. Developers are encouraged **not** to push directly to the `main` branch but instead create a new branch and submit a pull request. If you are working in a team, communicate with the administrator before merging into the `main` branch.

### Branch Naming Conventions

#### From the `main` Branch

Branches created from the `main` branch should follow this naming convention:


```
<alias>-<feature-name>
```

For example, if developer `John Doe` is working on a feature to add a new login page, the branch name should be:

```
jd-login_page
```


If `<feature-name>` consists of multiple words, use underscores `_` to separate them.

#### From Other Branches

If you are creating a branch from another branch, use the following naming convention:



```
<previous-branch-name>-<alias>-<feature-name>
```

Continuing with the previous example, if `Harry Houdini` wants to add an animation to the login page, the branch name should be:


```
jd-login_page-h2-animation
```

This naming pattern should be followed recursively. That means if another developer wants to add a new feature to `Harry Houdini`'s branch, the branch name should be:

```
jd-login_page-h2-animation-<alias>-<feature-name>
```
<!--
  - [2️⃣ Julia Development Standards](#2️⃣-julia-development-standards)
  - [3️⃣ MATLAB Coding Guidelines](#3️⃣-matlab-coding-guidelines)
  - [4️⃣ Python Best Practices](#4️⃣-python-best-practices)
  - [5️⃣ Quarto Documentation \& Reporting](#5️⃣-quarto-documentation--reporting)
  - [6️⃣ General Development Guidelines](#6️⃣-general-development-guidelines)
  - [7️⃣ References \& Additional Resources](#7️⃣-references--additional-resources)
---

## 2️⃣ Julia Development Standards  
- Code style and formatting (following `JuliaFormatter.jl`)  
- Best practices for structuring Julia projects  
- Writing efficient and type-stable Julia code  
- Using environments and dependencies (`Project.toml`, `Manifest.toml`)  
- Testing and debugging Julia code  

---

## 3️⃣ MATLAB Coding Guidelines  
- Script vs. function best practices  
- Code readability and documentation standards  
- Performance optimization techniques  
- Using version control with MATLAB projects  
- Handling dependencies and toolbox compatibility  

---

## 4️⃣ Python Best Practices  
- Code formatting (`Black`, `isort`, `flake8`)  
- Virtual environments (`venv`, `conda`)  
- Project structure and dependency management (`requirements.txt`, `pyproject.toml`)  
- Writing tests with `pytest`  
- Logging and debugging techniques  

---

## 5️⃣ Quarto Documentation & Reporting  
- Setting up and using Quarto for reports  
- Markdown and formatting best practices  
- Exporting to different formats (PDF, HTML, Word)  
- Embedding code and visualizations  
- Automating document generation  

---

## 6️⃣ General Development Guidelines  
- Code documentation (`docstrings`, comments, README files)  
- Error handling and debugging strategies  
- Performance optimization principles  
- Collaboration and communication best practices  

---

## 7️⃣ References & Additional Resources  
- Official documentation for tools and languages  
- Internal team templates and examples  
- Useful books, tutorials, and external resources  

---

Would you like any specific additions or modifications? 🚀  
-->