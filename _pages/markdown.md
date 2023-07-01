@@ -1,13 +1,13 @@
---
permalink: /markdown/
title: "Markdown"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Jekyll / theme guide
## Locations of key files/directories

* Basic config options: _config.yml
* Top navigation bar config: _data/navigation.yml
@@ -18,6 +18,9 @@ redirect_from:
  * _posts/
  * _teaching/
  * _talks/
* Footer: _includes/footer.html
* Static files (like PDFs): /files/
* Profile image (can set in _config.yml): images/profile.png

## Tips and hints

* Name a file ".md" to have it render in markdown, name it ".html" to render in HTML.
* Go to the [commit list](https://github.com/academicpages/academicpages.github.io/commits/master) (on your repo) to find the last version Github built with Jekyll. 
  * Green check: successful build
  * Orange circle: building
  * Red X: error
  * No icon: not built
## Resources
 * [Liquid syntax guide](https://shopify.github.io/liquid/tags/control-flow/)
## Markdown guide
### Header three
#### Header four
##### Header five
###### Header six

