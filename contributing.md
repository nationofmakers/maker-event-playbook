---
title: Contributing
keywords: homepage
tags: [getting_started]
sidebar: home_sidebar
permalink: contributing.html
summary: You can contribute to this playbook by adding to the playbook overview OR by documenting your own event.
---

{% include warning.html content = "NOTE, WE ARE NOT READY FOR YOU TO DO THIS, BUT WANTED TO CREATE THIS PAGE :)" %}

### Please start by reading ["Why GitHub"](why_github.html) to learn why we chose GitHub and GitHub pages for the Maker Event Playbook and how we are organizing the project using Open Source software principles

## Contribute to the playbook overview sections  
This playbook has both an overview context and documentation from specific events. Use the steps below to contribute to the overview sections.

### Suggestions & Corrections
#### You can make suggestions or propose corrections by creating GitHub issues for this repository. Please check to see if existing issues exist for this item, and please be specific.

### Changes
To directly contribute changes to the Maker Event Playbook, do the following:
{% include important.html content = "If you are wanting to create a version of the playbook for your event, head straight to [Documenting Your Event](documenting_your_event.html)" %}


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

2. Build the site with jekyll
```bundle exec jekyll serve```

3. Load your site in a brower. Note that the url for the site will include /maker-event-playbook such as http://127.0.0.1:4000/maker-event-playbook/

4. Note that as you edit and resave files, jekyll with automatically rebuild and update (fancy!)


####  3. Make updates
Make changes to the overview pages. Please make impactful changes only, and keep overview pages generic and global in scope. See the "Contribute by documenting your event" section below to learn how to make changes specific to your event.

#### 4. Create a pull request
Once you've reviewed and commited your changes, create a granular pull request so that we can review and incorporate the changes.


## Contribute by documenting your event  

See the [Documenting Your Event](documenting_your_event.html) page for details on how you can integrate your event's documention into this global playbook, while also creating a version specific to your event!
