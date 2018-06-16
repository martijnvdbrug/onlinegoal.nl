# Onlinegoal.nl
Jekyll source for onlinegoal.nl based on 
[Jekyll Materialize starter template](https://github.com/macrod68/jekyll-materialize-starter-template) by Marco Damiani   

## plugins
`gem install jekyll-sitemap`
`gem install jekyll-seo-tag`

## Custom includes
Custom html includes used on this site

#### Call to action
A call to action include exists and can be used as follows:
```
{% include cto.html href="/proposities-testen" text="Klik hier" icon="flash_on" %}
```
Parameters: 
* `href` is the relative link for the button
* `text` is the text on the button
* `icon` is the material icon used in the button
