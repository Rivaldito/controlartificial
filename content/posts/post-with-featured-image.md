---
title: "Post With Featured Image"
date: 2018-10-01T16:15:09+08:00
draft: false
images: 
  - https://cdn.pixabay.com/photo/2015/11/05/06/14/background-1023739_960_720.jpg
tags: 
  - Demo
  - Image
---

Just define the image URL in the content’s front matter, the featured image will be displayed as the background. 

For example:

```yaml
---
images:
  - https://picsum.photos/1024/768/?random
---
```

```Python
print hola
```

This is an array, you can set multiple urls, only the first url will be used. These images is also used in [Twitter Cards](https://developer.twitter.com/en/docs/tweets/optimize-with-cards/guides/getting-started.html) and the [Open Graph](http://ogp.me/) metadata.
