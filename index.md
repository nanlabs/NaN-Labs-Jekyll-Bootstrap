---
layout: project
page: project
title: "NaN Labs - Jekyll Bootstrap"
description: "A project to bootstrap NaN Labs Github Pages."
home-text: Home
footer-title: Get in touch
logoImg: logo-195x120.png
section: project
header: "Jekyll Bootstrap"
lead-text: "A project to bootstrap NaN Labs Github Pages."
github-url: "https://github.com/nanlabs/NaN-Labs-Jekyll-Bootstrap"
---
This project is based on <a href="http://jekyllbootstrap.com/" target="_blank">Jekyll Bootstrap</a>, but using NaN Labs style and layouts.
The mode of use is similar to Jekyll Bootstrap, but using <a href="http://rake.rubyforge.org/" target="_blank">Rake</a> to allow the user to generate project pages.

#### Mode of use:
1. *git clone git@github.com:nanlabs/NaN-Labs-Jekyll-Bootstrap.git ghPage*
2. *cd ghPage*
3. *git remote set-url origin __project-clone-url__*
4. *git branch gh-pages*
5. *git checkout gh-pages*
6. *git push origin gh-pages*

Once you have done this, in order to create a project page you only need to run the following rake command:

*rake project title="project-title" [description="project-description"] [repourl="repository-url"]*
