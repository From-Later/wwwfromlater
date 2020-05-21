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

## TODO:
- [ ] @uditvira to add deployment instructions
