# Version Control

Version control is an invaluable piece of technology used by software developers worldwide. It allows development teams to coordinate their efforts, divide up work, review one another's code, undo mistakes, run experiments, and view every change that's ever been made to the code. Working as a team on almost any project without a version control system would be very difficult, and even when working alone, version control provides insurance against mistakes (of any size) or computer crashes.

GitHub is a web interface to the Git version control system. Git was initially built in 2005 by Linus Torvalds, and is a complex, very capable system. Git itself is mostly used through the command-line terminal, but GitHub allows developers and account managers alike to view the code, create and discuss issues, and manage versions.

This section is a quick overview of how Git works, and how those features show up on the GitHub site.

## Why use version control?

A team (of developers and one or more account managers) working together on a project has a few challenges to address before we can get anywhere.
- How do we divide up and assign work?
- How do the developers keep each other's code up to date?
- What happens if two developers change the code at the same time?  (This happens constantly.)
- How do you, as the account manager, understand and keep track of what's going on?
- How do developers review each other's code, for quality and style consistency?

Git and GitHub solve all of these problems.

Git itself allows a definitive version of the code to be kept in a secure remote location. Developers can download this code, modify it, and then submit their changes to Git for review. These changes show up on GitHub for everyone else on the team to look at; the code can be reviewed, changed as necessary, and then eventually combined into the definitive version. Developers can then update the code on their computers from Git whenever they want to. This neatly addresses all the problems with keeping up to date and working on the code simultaneously; any number of people can submit concurrent changes to Git, and even if those changes clash, the conflicts can be automatically or manually resolved.

You as an account manager can view the changes on GitHub as they come in, and use the website to open *issues* for the developers to address. An issue represents a piece of work - adding a small feature, fixing a bug, making a change requested by the client. Developers can then link submitted changes to an issue, making it easier for them and you to track what's being done to fix it.

Without version control, coordinating the team's efforts would become very difficult. GitHub goes above and beyond the typical advantages of a version control system by allowing for discussion and streamlined division of work. It's all upside.

## Repositories

The central store of code is organised around *repositories*, each of which houses everything needed for a self-contained project. A repository contains the main version of the project code (usually referred to as *master*), any number of alternate versions being worked on (called *branches*), and lots of historical information. It will have a page on GitHub; from that page, you can view and download the code, submit issues, manage people assigned to the project, and more.

For instance, here's an example of a repository home page:

`![todo: image]()`

The central box displays the code in the repository as a list of files and folders, and a variety of links and buttons around it navigate you to the various tasks you might want to perform. The lists of files and branches will update as developers submit modifications via Git, and you can refresh the page to see the changes.

Because each repository represents a single project, an individual developer will rarely need to work on multiple repositories together; typically, one repository contains everything for, say, a particular site's front-end or a complete back-end API (which may or may not be used by multiple sites).

## Commits

## Master and branches

## Merging

## Pull requests
