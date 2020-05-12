---
title: Contributing
keywords: homepage
tags: [getting_started]
sidebar: home_sidebar
permalink: /contribute/contributing
summary: You can contribute to this playbook by adding to the playbook overview OR by documenting your own event.
---

{% include warning.html content = "NOTE, WE ARE NOT READY FOR YOU TO DO THIS, BUT WANTED TO CREATE THIS PAGE :)" %}

### Why GitHub

["Why GitHub"](why_github)to learn why we chose GitHub and GitHub pages for the Maker Event Playbook and how we are organizing the project using Open Source software principles

### How The Maker Event Playbook uses GitHub Repos and GitHub pages
[![The Maker Event Playbook on GitHub Diagram](/images/overview/maker_event_playbook_github_basics_v5_small.jpg)](/maker-event-playbook/images/overview/maker_event_playbook_github_basics_v5.pdf)

### The Maker Event Playbook uses several key components of GitHub to store and serve the playbook.
* GitHub "Repo" - A GitHub repository (repo) provides storage with version control for Open Source code (that’s our playbook documentation pages), media and more. GitHub also tracks “issues” which are things to add or fix within our repo.
* GitHub "Fork" - If you want to contribute to the Maker Event Playbook (or any GitHub Open Source project), you first create your own working copy of the repo. This is called “forking” the repo and your working copy is referred to as a “fork” of the original repo.
* GitHub "Commit" - Once you’ve made a set of related changes to your repository (and tested them!) you commit the change along with notes explaining the change. GitHub stores these commits in your repo and you can easily see the change history, or undo a commit later.
* GitHub "Pull Request" - Once you’ve finished making changes in your fork, you can create a GitHub Pull Request. This is a request to the maintainers of the playbook, essentially saying “I’ve made an update, will you pull changes from my repo and merge them back into the original repository”

### Contribute
You can contribute by:
* Contributing new pages or changes to existing pages that are part of the overall Maker Event Playbook.
* Creating a playbook specific to your maker event or organization


**Contribute new pages or changes to existing pages that are part of the overall Maker Event Playbook**
This playbook has both an overview context and documentation from specific events. Use the steps below to contribute to the overview sections.

### Suggestions & Corrections
**You can make suggestions or propose corrections by creating GitHub issues for this repository. Please check to see if existing issues exist for this item, and please be specific.**

### Changes
To directly contribute changes to the Maker Event Playbook, do the following:
{% include important.html content = "If you are wanting to create a version of the playbook for your event, head straight to [Documenting Your Event](document_your_event.html)" %}


#### 1. Fork this repo
Use GitHub tools to fork this repo into your account.

#### 2. If you will be making minor changes to content:
You can view your repo using GitHub pages, and make simple changes in the GitHub web editor (or clone, edit and push to your repo)
1. Enable GitHub pages using settings for your repository
2. Verify that the repository built properly (status in settings)
3. View your pages (link in settings, or under environment)

#### 3. If you will be making code or large content changes:
You will want a local build environment where you can clone your repo, make changes, and see those changes in realtime without waiting for GitHub to rebuild. This will also make your changes easier to pull back to the main repo since your commits will be much more logical.

1. Setup a local build environment
[This guide](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll#step-2-install-jekyll-using-bundler) from GitHub is super helpful for setting up your build environment.

2. Build the site with Jekyll
```bundle exec jekyll serve```

3. Load your site in a brower. Note that the url for the site will include /maker-event-playbook such as http://127.0.0.1:4000/maker-event-playbook/

4. Note that as you edit and re-save files, Jekyll with automatically rebuild and update (fancy!)


####  3. Make updates
Make changes to the overview pages. Please make impactful changes only, and keep overview pages generic and global in scope. See the "Contribute by documenting your event" section below to learn how to make changes specific to your event.

#### 4. Create a pull request
Once you've reviewed and committed your changes, create a granular pull request so that we can review and incorporate the changes.


### Contribute by creating a playbook for your organization's event(s)

See the [Documenting Your Event](document_your_event.html) page for details on how you can integrate your event's documentation into this global playbook, while also creating a version specific to your event!
