# JohnnyMatthews.dev

This repo holds the [Hugo files](https://gohugo.io) and styling for [johnnymatthews.dev](https://johnnymatthews.dev). The blog _content_ lives in [github.com/johnnymatthews/blog](https://github.com/johnnymatthews/blog).

## Dear Future John

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
Past John.
