# Bootstrap 4
BS4 is a project setup for professional front-end template designer, and to build
fast, robust, and adaptable web apps or sites.


## Quick start
Run following command in cmd or terminal:
1. Clone the git repo - 
    `git clone https://github.com/barthwal/bs4.git`
2. Install dev dependency - `cd bs4 && npm install`
3. Run web server - `gulp`


## Features
* Bootstrap 4 Theming setup with sass
* gulp and browser-sync plugin used to make it easy and fast.


## Browser support
* Chrome
* Edge
* Firefox
* Internet Explorer 9+
* Opera
* Safari


## Documentation
#### HTML
* You can create folders and add files in the "src" folder (any file structure you want).
* I have created the template.html file in "src" folder, which will be used as a base for your template page.

#### CSS
* You can write all of you css style in "scss/style.scss" file and when you run gulp then all scss code pre-process and copied to "css/style.css" which is included in html file.
* All the bootstrap 4 lib css code is already included in "scss/style.scss" file. Check this line - `@import "../../node_modules/bootstrap/scss/bootstrap";` in style.scss.
[note: If you dont want your bootstrap 4 css code include in "css/style.css" file.]

