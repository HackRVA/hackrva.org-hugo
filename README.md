# HackRVA website
This site is built with [hugo](https://gohugo.io/). A static site generator written in Go.

Don't worry, it is very simple to work with.  Most of the site can be modified in html and css.
Hugo also has [shortcodes](https://gohugo.io/content-management/shortcodes/) which 

## Setup
### Prerequisites
* You will need some version of nodejs installed (probably greater than v12).
* You will need to install golang. Follow instructions @ https://golang.org/dl/
* Install Hugo extended version.  This is just a binary https://github.com/gohugoio/hugo/releases

### Install dependencies
* install the theme ` git submodule update --init --recursive `
* install node dependencies ` npm ci `

## Run the site

```
hugo server
```

## Build the site
```
hugo
```
> note: this will output to a dir called `public` which can be served up by most common web servers