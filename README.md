# About
Liquid Response is a minimalistic CSS framework with mobile-first take. 

Liquid Response is a personal selection of best practices from popular, open-source grid frameworks wrapped into a mobile-first approach and published with the hope of being useful to others.

Liquid Response is distributed under MIT license.

# Installation

1. cd css (or whatever your CSS folder is)
1. Download zip file and unzip or: 'git clone git@github.com:inadarei/liquidresponse.git'
1. cd liquidresponse (or go into "liquidresponse folder")
1. mv responsive.default ../responsive (or: move "responsive.default" folder one level up, in the folder structure, and rename it to just "responsive")
1. Add lines similar to the following to your HTML head:
<code>
<br/>
&lt;meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1"/&gt;
<br/>
&lt;link href="/css/liquidresponse/liquidresponse.css" media="screen" rel="stylesheet" /&gt;
</code>
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
