# JohnnyMatthews.dev

[![Netlify Status](https://api.netlify.com/api/v1/badges/91429c32-08ed-484a-88f6-3eb9b37df31a/deploy-status)](https://app.netlify.com/sites/dainty-nougat-cbd492/deploys)

This repo holds the [Hugo files](https://gohugo.io) and styling for [johnnymatthews.dev](https://johnnymatthews.dev). The blog _content_ lives in [github.com/johnnymatthews/blog](https://github.com/johnnymatthews/blog).

## Dear Future Johnny

You need to run the following stuff every time there's a new blog post in [`johnnymatthews/blog`](https://github.com/johnnymatthews/blog) and you've had to reclone this repo again:

```shell
git submodule init
git submodule update --recursive --remote
cd content/blog
git checkout yolo
git pull
cd ../..
```

Love, 
Past Johnny.
