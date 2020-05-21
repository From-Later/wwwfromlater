# Websites for fromlater.com

From Later's websites are built using [Jekyll](https://jekyllrb.com/)–a markdown based simple static site generator.

## What's in this repository?
This repository currently contains Jekyll codebases for the following web domains:

1. `fromlater.com` (`www.fromlater.com` is also aliased), whose codebase can be found in [wwwfromlater/homepage](https://github.com/From-Later/wwwfromlater/tree/master/homepage)
2. `views.fromlater.com`, whose codebase can be found in [wwwfromlater/viewsfromlater](https://github.com/From-Later/wwwfromlater/tree/master/viewsfromlater)
3. `recordings.fromlater.com`, whose codebase can be found in [wwwfromlater/recordingsfromlater](https://github.com/From-Later/wwwfromlater/tree/master/recordingsfromlater)

The [wwwfromlater/shared](https://github.com/From-Later/wwwfromlater/tree/master/shared) directory contains code that is shared between the three websites

## Prerequisite to setup
* Be familiar with version control with Git and GitHub. See the [Software Carpentry online lessons](https://swcarpentry.github.io/git-novice/) if you're a novice
* Check and make sure you [meet requirements to run Jekyll](https://jekyllrb.com/docs/). You'll need to have an appropriate version of Ruby installed

## Set up locally on your machine
1. Clone the repository with `git clone https://github.com/From-Later/wwwfromlater.git`
2. Navigate to any of the main web directories by first `cd wwwfromlater` and then `cd homepage`
3. Build Jekyll code by `jekyll build`
4. Serve locally by `jekyll serve`
5. You should see a message like: 
```
Server address: http://127.0.0.1:4000/
Server running... press ctrl-c to stop.
```
6. Navigate to `http://127.0.0.1:4000/` on your browser to see if it worked

## Contribution Guidelines
Everyone is welcome to make pull requests! Our process for accepting changes has a few steps:

1. If you haven't submitted anything before, start by cloning the repository. Organization members should clone the upsteam repo, instead of working from a fork:

        git clone https://github.com/From-Later/wwwfromlater.git

2. Create a new branch for the changes you want to work on. Choose a topic for your branch name that reflects the change:

        git checkout -b <branch-name>

3. Create or modify the files with your changes. If you want to show other people work that isn't ready to merge in, commit your changes then create a pull request (PR) with __WIP__ in the title.

        https://github.com/From-Later/wwwfromlater/pull/new/master

4. Once your changes are ready for final review, commit your changes then create or modify your PR.

5. Allow others sufficient time for review and comments before merging. For big changes, ping @uditvira to check over what you've done. There may be some fixes or adjustments you'll have to make based on feedback.

6. Once you have integrated comments, or waited for feedback, merge away!

## TODO:
- [ ] @uditvira to add deployment instructions
