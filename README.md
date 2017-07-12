# EMBL Design Language homepage (springboard)
Where to go to find out what you need to know about using the Language, its rules, templates and governance.

See it at https://embl-design-language.github.io/Springboard/

## Developing the Springboard

### The CMS bit

The Springboard is a "Jekyll" site and is built using GitHub's "Pages" feature. That is: GitHub compiles everything in the gh-pages branch into html and serves it up at https://embl-design-language.github.io/Springboard/

### The styling bit

The look and function of the site comes from three areas:

1. The Jekyll template files in this branch inside `_layouts` and `_includes`
2. This branch's local CSS and JS (`css/app.css`, `js/app.js`)
3. The `Framework-for-Websites` repo, more on that below

#### The Framework-for-Websites repo

<a href="https://github.com/EMBL-Design-Language/Framework-for-Websites">The Framework-for-Websites repo</a> is an instantiation of <a href="https://github.com/zurb/foundation-sites">Foundation for Websites</a>.

Any changes you apply to the files inside the local `scss` and `js` directories <a href="https://travis-ci.org/EMBL-Design-Language/Framework-for-Websites">will be compiled by Travis CI</a> and served as:
- CSS: https://embl-design-language.github.io/Framework-for-Websites/css/embl-design-language-framework.css
- JS: https://embl-design-language.github.io/Framework-for-Websites/js/embl-design-language-framework.js

For more background, head to: https://github.com/EMBL-Design-Language/Framework-for-Websites
