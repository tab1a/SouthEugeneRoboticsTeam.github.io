# SouthEugeneRoboticsTeam.github.io

## Introduction
This is the new SERT website. You may visit it at [sert2521.tk](https://sert2521.tk).

## Contributing
If you would like to contribute to the website, please fork this repository, make your changes,
and submit a Pull Request.

## Jekyll
This website uses [Jekyll](https://jekyllrb.com). You can find documentation on Jekyll [here](https://jekyllrb.com/docs/home/).

## Creating a Blog Post

To add a blog post to the website, add a file to the `/_posts/` directory named using the following format:
`YYYY-MM-DD-TITLE.md`. For example, a post with the title "Test Post" written on August 21st, 2016
would be named `2016-8-21-test-post.md`.

The contents of this post should follow the following format (note - the content of the blog post may use
HTML tags or Markdown):

```html
---
  layout: post
  title: TITLE
  tags: [ARRAY,OF,TAGS]
  categories: [ARRAY,OF,CATEGORIES]
  css:
    - post.css
---
Content here
```

For example, `2016-8-21-test-post.md`'s contents could be (written in Markdown):

```html
---
  layout: post
  title: my article title
  tags: [test]
  categories: []
  css:
    - post.css
---

### Lorem ipsum dolor sit amet

[Link](http://google.com)

![Image](http://i.imgur.com/BbA9Fsl.png)

This is a test post! Hopefully everything works out well! Lorem ipsum dolor sit amet, et quam, nibh in lacus
maecenas vestibulum, nam cras orci quis, vitae arcu nisl neque sed lectus. Mi pellentesque neque, ornare sit
porttitor quia leo lectus pulvinar, dapibus mi mauris in ac, sem pede lorem ante wisi a magna.
[...]
```

If you don't feel like making the post yourself, base posts may be easily generated using the following commands:

```bash
$ cd SouthEugeneRoboticsTeam.github.io
$ npm install -g jekyll-posts-generator
$ jposts create-post 'my title here'
```

Read the official documentation on posts [here](https://jekyllrb.com/docs/posts/).