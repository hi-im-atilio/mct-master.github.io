# mct-master.github.io

The blog of MCT.

We are using [Jekyll](https://jekyllrb.com/), here's a list of tutorials that might be useful to get familiar with the GitHub and Jekyll environments:

* [Using GitHub to Create and Host a Personal Website](http://jmcglone.com/notes/2014/05/03/using-github-to-create-and-host-a-personal-website)
* [Creating and Hosting a Personal Site on GitHub](http://jmcglone.com/guides/github-pages/)
* [Quick Start Guide with Jekyll](https://jekyllrb.com/docs/quickstart/)

To edit the site you have to contribute your changes (e.g., posts) to this source code repository. After your changes are committed and merged to the master branch, Github will automatically rebuild the static site and make it instantly available to the public. Note that editing existing contents and adding new contents can be all done directly from the Github web interface. It is therefore not strictly needed to clone the repository and install the required software to edit the site locally. [Here](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/) you can find instructions for setting up a local copy of a Github Pages site.

The content of the site is released under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/).

## Instructions for contributing to the MCT site

### Posting in the "home" section

You can add a news post by creating a file in the [_posts](https://github.com/MCT-master/mct-master.github.io/tree/master/_posts) folder of this repository.
Note that you can directly create the file from the Github web interface by navigating to the [_posts](https://github.com/MCT-master/mct-master.github.io/tree/master/_posts) folder and clicking on the **New file** button.
The file must be markdown formatted and must include a number of metadata fields in a YAML front matter (see example below).
It must be named as `YYYY-MM-DD-short-version-of-title.md` (YYYY-MM-DD being the publication date).
Once the file is saved and committed to the `master` branch (Github web interface will do it for you upon saving the newly created file), it will automatically be added to the news section (it may take a few seconds).

Required structure of the markdown file for a news post:

```markdown
---
layout: post
title: "Welcome to Jekyll!"
date: 2018-08-21 10:10:42 +0200
categories: jekyll update
author: Name Surname
---

Add the post body here using markdown syntax.
```

Check [Github's markdown syntax guide](https://guides.github.com/features/mastering-markdown/) for examples on how to format text with markdown.

Existing news entries can also be easily edited by navigating to the file with the Github web interface and clicking on **Edit this file** (i.e., the icon with a pencil). When changes are committed to the `master` branch the post will be automatically updated on the site.

Images and other assets (e.g. css, files, javascript files) can be organized in the [assets folder](https://github.com/MCT-master/mct-master.github.io/tree/master/assets).

## Examples of similar masters

* https://www.smc.aau.dk
* https://www.upf.edu/web/smc
* http://www.gtcmt.gatech.edu
* http://ied17.rca.ac.uk

## Examples of blogs

* https://rcaied.tumblr.com: Here's an example of a mostly visual blog from a master (master in information experience design from RCA).

* http://womeninmusictech.gatech.edu: A blog built in Wordpress of multiple authors (the newsletter of Women in Music Tech at Georgia Tech).
* https://midassblog.wordpress.com: A blog built in Wordpress of multiple authors (the blog of the research project MIDAS).
