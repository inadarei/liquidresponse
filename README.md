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

# Advanced Installation for Git Projects

If you manage your project in Git, you may want to "attach" liquidresponse as a Git submodule, for easier updates:

1. git submodule add https://github.com/inadarei/liquidresponse public/css/liquidresponse
1. git init public/css/liquidresponse
1. git commit -m "adding liquidresponse as proper submodule" .
1. git push

ATTENTION: these commands must be run from the root of your git working copy. Also please note
that I am "installing" liquidresponse in "public/css/liquidresponse" folder under my web root.
You will have to adjust that to suit your project.

Once you have liquidresponse set up as a git module, you can update it with:
`git submodule update --init public/css/liquidresponse` (again: fix path) or:
`git submodule update --init` if you are OK with updating all submodules.

# Usage 
