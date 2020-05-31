# CodeWithAti

## Website

This is www.codewithati.com website sourece coee. CodeWithAti is where I (Ati) write blogs articles and share with you.

I am using a static site generator (SSG) called jekyll. For more information checkout [jekyll website](https://jekyllrb.com/). I have also used a theme for my website called beautiful jekyll for more information please [Check out beautiful jekyll website](https://beautifuljekyll.com). 

### Setup development environment

#### Requirements

- docker

Clone this repository and checkout `gh-pages` branch. 

Run following command in the same directory you cloned this repository. 

```
export JEKYLL_VERSION=3.8
docker run --rm \
  --publish="4000:4000" \
  --volume="$PWD:/srv/jekyll" \
  -it jekyll/builder:$JEKYLL_VERSION \
  jekyll serve
```

Open http://0.0.0.0:4000 in your browser.