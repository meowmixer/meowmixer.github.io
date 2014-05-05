meowmixer.github.io
===================

A cat's blog

## Setup
* Install [jekyll](http://jekyllrb.com/)
* Install [jekyll-tools](https://github.com/jasonrhodes/jekyll-tools)
  ```bash
  sudo npm -g install jekyll-tools
  ```

## Development
* git clone this repo
* All work must be done on the develop branch: ```git checkout develop``` Do NOT work on master!
* ```jekyll serve --watch```
* Make changes, eg: add posts, modify css, add images, etc.
* When it looks good, run:
  ```bash
  git add .
  git commit -m "descriptive commit message"
  git push origin develop
  jek deploy
  ```

  The last line invokes [jekyll-tools](https://github.com/jasonrhodes/jekyll-tools)
  to build the site and pushes the contents of ```_site``` folder to master.
