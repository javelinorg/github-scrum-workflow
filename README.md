<img src="https://cloud.githubusercontent.com/assets/1859381/5397698/9972fe22-815c-11e4-8be6-21e1d0d05849.jpg" alt="codecat" align="right">

# GitHub scrum workflow

*This is a fork of the work done by jvandemo and his [documentation](https://github.com/jvandemo/github-scrum-workflow)*

Turn any GitHub repository into a simple but powerful agile work environment.

**Free**, **simple** and **fast** so you can focus on the actual coding!

**Summary:**

+ [How it works](#how-it-works)
+ [1. Create issues as backlog items](#1-create-issues-as-backlog-items)
+ [2. Add labels to issues](#2-add-labels-to-issues)
+ [3. Define milestones as user stories](#3-define-milestones-as-user-stories)
+ [4. Define pojects as sprints](#3-define-projects-as-sprints)
+ [Overview](#overview)
+ [Helpful links](#helpful-links)
+ [Change log](#change-log)

---

## How it works

- Backlog Items are reported as **issues**.
- User Story Points (complexity) and meta data are assigned to Backloag Items as **labels**.
- **Projects** are used to group issues in sprints.
- **Milestones** are used by the Product Owner to capture Product Features and their associated Backlog Items **issues**.

## 1. Create issues as backlog items

To create a new backlog item, just create a new issue.

Once a new issue has been created, assign it the right labels and assign it to a milestone.

Issues allow you to have a conversation about the item and even allow you to create task lists inside the issue using [GitHub's markdown](https://guides.github.com/features/mastering-markdown/).

## 2. Add labels to issues

Add the following labels to your repository:

### Priorities

`priority` labels allow you to prioritize items in your backlog e.g.:

- `priority: lowest`
- `priority: low`
- `priority: medium`
- `priority: high`
- `priority: highest`

### Points

`point` labels allow you to to assign velocity points to individual items (issues) e.g. using [Fibonacci numbers](http://en.wikipedia.org/wiki/Fibonacci_number):

- `point: 1`
- `point: 2`
- `point: 3`
- `point: 5`
- `point: 8`
- `point: 13`
- `point: 21`

### Types

`type` labels allow you to easily filter items (issues) in the dashboard e.g.:

- `type:bug`: bug
- `type:chore`: chore, maintenance work
- `type:feature`: new feature
- `type:infrastructure`: infrastructure related
- `type:performance`: performance related
- `type:refactor`: refactor
- `type:test`: test related

### Other

You can define and assign custom labels that you need within your workflow or organization.

## 3. Sprints are defined as GitHub Projects

You can create a Project for every Sprint and add backlog items (issues) to the Project during the planning phase of the Sprint.

This allows you to group items in sprints and track their progress inside your repostory via the GitHub Projects view as well as GitHub Milestones.

The backlog then consists of all items (issues) that have no `milestone` attached to it.

**TIP**: Use `no:milestone` in the search field on your [issue dashboard](https://github.com/issues) to find backlog items.

## Scrum Overview

![en_overview](https://cloud.githubusercontent.com/assets/1859381/5411950/c44c229e-8207-11e4-915f-d31ccd66c5bd.png)

Image: [Scrum primer](http://www.scrumprimer.org/overview).

## Helpful links

- [Mastering GitHub issues](https://guides.github.com/features/issues/)
- [Mastering GitHub markdown](https://guides.github.com/features/mastering-markdown/)
- [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/)

## Change log

### v1.0.0

- Added documentation for issues, labels and milestones.

### v1.0.1

- Added summary

### v1.1.0

- Reorganized GitHub feature usage to better aling with Scrum methodology