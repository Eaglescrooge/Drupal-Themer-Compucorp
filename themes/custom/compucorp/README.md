Open-Charity Drupal 8 website
Steps
I developed this site using Html and Css(2 Dimensiolanl Grid System -"Rows and Columns").
 For the Desktop and tablet screen ,i used columns which comes with their respective width.
.col-1 {width: 8.33%;}
.col-2 {width: 16.66%;}
.col-3 {width: 25%;}
.col-4 {width: 33.33%;}
.col-5 {width: 41.66%;}
.col-6 {width: 50%;}
.col-7 {width: 58.33%;}
.col-8 {width: 66.66%;}
.col-9 {width: 75%;}
.col-10 {width: 83.33%;}
.col-11 {width: 91.66%;}
.col-12 {width: 100%;}
 


Other screen was adjusted using the same 2 Dimensional Grid System- Rows and Columns.For the mobile screen images that were floated up,were given attribute of Float:none.
This was done so as to enable my user have a lovely experience using the product.
 
Local Development Services was changed so disable caching and be able to debug.
parameters:
  twig.config:
      debug: true
      auto-reload: true
      cache: false
This site was hosted using Amazon web service and the site IP address -http://18.216.240.253/
Configure the info yml file to this
name: compucorp
description: Drupal 8 theme
type: theme
core: 8.x
libraries:
  - compucorp/global-css
stylesheets-remove:
    - sites/default/files/css/css_Cq6GZMKk1r9hD6Tpeso65Tb4UrBQbPvUhNvc2pJ21KY.css

Libraries for the theme
global-css:
    css:
      theme:
        css/style.css: {}


        



	