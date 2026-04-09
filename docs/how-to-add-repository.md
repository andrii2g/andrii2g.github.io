# How to Add a New Repository

This guide describes the full workflow for adding a new repository to the catalog website.

- Create a new repository in GitHub
- Inside the repository, create a clear README.md:

What it does. Why it exists. How to run it. Tech stack. Example usage

- Add a page to the catalog site

Create a new file (docs/repositories/<repository-name>.md) by using the following template

```markdown
---
tags:
  - put
  - proper
  - tags
  - here
---

# Repository Name

## Summary
Short summary about the repository

## Purpose
The main goal of this project

## GitHub
direct link to GitHub page

## Status
Status of the project (Active, Inactive, any others)

## Tech stack
- put
- tech
- stack
- here

## Features
- put
- features
- here

## Next ideas
- put
- next
- ideas
- if any, if applicable
```

- Add repository to navigation

Open mkdocs.yml, add repository under the nav->Repositories in format "repository-name: repositories/repository-name.md"

- Add to category page

open existing category file matched to repository meanings, or create a new category file under the docs/categories folder and update content by using the following template

```markdown
# Category name

Put description of the category here

## Repositories

Put a list of repositories related to this category in format
- [repository-name](../repositories/repository-name.md)
```
