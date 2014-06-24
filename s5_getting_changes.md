< Previous section: [Creating a project](https://github.com/rogerhutchings/github-for-account-managers/blob/markdown/s4_creating_projects.md)

---

# 5. Getting changes made to your project

Sooner rather than later, you're going to need to ask a developer to make a change to a project, whether that's adding a whole new feature, or fixing a typo you've spotted. To do that, you'll need to create an __issue__. 

In the Version Control section, we talked about a commit being the basic unit of work for a developer. Think of an issue as being the basic unit of a project.

At heart, an issue is simply _a single actionable task_. A big, complex feature might require multiple issues to implement. Lots of small changes will require an issue for each change.

The reason for this is efficiency - a single task can be picked up by the next free developer and worked on, ideally without impacting anyone else's work. Trying to assign a complex task to different people inside the same issue can result in confusion, mistakes, and code conflicts where people change the same files.

## What makes a good issue?

- __A good title__<br>
    An issue title should be long enough that the issue can be understood without having to read the description. If you can include where in the project the issue lies, even better. For example:
    > Home page - Missing RSS icon on news widget title bar

- __Detail__<br>
    Add as much detail as possible - clicking around a site trying to find something, or work out what actually needs changing, means less time for a developer to fix your issue.

    An easy way to do this is to add a screenshot. [Awesome Screenshot](http://awesomescreenshot.com/) is great for taking and annotating screenshots in the browser. You can then drag and drop it into GitHub to add it to your issue.

- __Reproducibility__<br>
    A dev needs to be able to observe a problem in order to troubleshoot it. If you have a problem that comes and goes, spend some time to isolate the cause - transient bugs are incredibly difficult to fix.
    > Bad: Top navigation breaks sometimes<br>Good: Top navigation won't open when side navigation is already open

## When to reopen an issue

We've already talked about an issue being a single actionable item. If there's a problem with the way an issue has been closed &ndash; a content change has been missed out, for example &ndash; then reopening an issue is valid, as long as there's also a comment explaining why.

If the issue changes significantly, it's no longer a single item, and a new issue is needed.

## When to mention people

GitHub has a useful feature to alert specific people to an issue by including `@username` in the body of the issue. This is great for asking people to contribute if you have a question for them, for example.

Avoid using them to assign people to an issue, however. Issues get picked up by whoever's available, and that might not be the person you just @'d! 

## Issue and comment formatting

GitHub uses a formatting language called Markdown to add text styles like bold, italic, lists and so on. See GitHub's [Markdown Basics](https://help.github.com/articles/markdown-basics) article to see what it can do.

--- 

Next section: [Meeting deadlines](https://github.com/rogerhutchings/github-for-account-managers/blob/markdown/s6_meeting_deadlines.md) >
