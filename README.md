# Source of Eralp Karaduman's CV

## [eralpkaraduman.github.io/cv](https://eralpkaraduman.github.io/cv)

[![Build Status](https://travis-ci.org/eralpkaraduman/cv.svg?branch=gh-pages)](https://travis-ci.org/eralpkaraduman/cv)

This is a fairly modified version of
[elipapa's markdown-cv](http://elipapa.github.io/markdown-cv) project.  
Which is using [jekyll](https://jekyllrb.com) to host the cv as static site on github.

My version simply uses
[sindresorhus's github-markdown-css](https://github.com/sindresorhus/github-markdown-css) the close
replica of github's markdown style. 


**Automatic PDF version generation**
Also if you set up Travis CI, i configured it up so after every commit, travis will print it to `cv.pdf` then create a release on github. You can always link to the latest release by adding the sufffix `/releases/latest` to repo url.
[/releases/latest](https://github.com/eralpkaraduman/cv/releases/latest)
[/releases/latest](releases/latest)


**If you want to have your own, just fork this repo and modify the `index.md`.**

## Running jekyll locally
(You don't need to run it locally to update this, do it on github's web ui)  
You should look at [jekyll's own documentation](https://jekyllrb.com/docs) but,
this is how you'd get started;  

`bundle install`  
`bundle exec jekyll serve --host=0.0.0.0`

