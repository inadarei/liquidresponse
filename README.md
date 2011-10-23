# About
Liquid Response is a response to my frustration that none of the major CSS Grids (as much as I like them) take mobile-first approach. 

Liquid Response is a personal selection of best practices from popular, open-source grid frameworks wrapped into a mobile-first approach and published with the hope of being useful for others.

Liquid Response is distributed under MIT license.

# Installation

1. cd css (or whatever your CSS folder is)
1. git clone git@github.com:inadarei/liquidresponse.git
1. cd liquidresponse
1. mv responsive.default ../responsive
1. Add a line similar to following to your HTML head:
`<link href="/css/liquidresponse/liquidresponse.css" media="screen" rel="stylesheet" type="text/css" /> `
1. Start using and give feedback.

## Advanced (for Git projects/users)
If you want to manage updates easily and your project is already checked into Git, following steps can give you
an idea about how to "attach" liquidresponse to your git repo as a git submodule (ATTENTION: these commands MUST
be run from the root of your working copy and in this example I am "installing" liquidresponse under 
"public/css/liquidresponse" below the root of the working copy. Modify this path to fit your project):
1. git submodule add https://github.com/inadarei/liquidresponse public/css/liquidresponse
1. git init public/css/liquidresponse
1. git commit -m "adding liquidresponse as proper submodule" .
1. git push

# Usage 
