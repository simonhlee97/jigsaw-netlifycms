---
title: 08 - Cloudinary Media Library
date: 2020-05-18T00:00:00.000Z
tags:
  - cloudinary
image: https://res.cloudinary.com/artisanstatic/photos.jpg
comments: true
---
Register on [Cloudinary](https://cloudinary.com/invites/lpov9zyyucivvxsnalc5/qq2slabgpy590znlop4j).

Go to `config.php`, add your **cloud name** and **API key** under the `services` key.

Now you can use the `media()` helper in your Blade templates to easily reference files in your Cloudinary library.

```html
<img src="{{ media('logo.png') }}">
<!-- is the same as -->
<img src="https://res.cloudinary.com/YOURCLOUDNAME/logo.png">
```

Cloudinary is also integrated into Netlify CMS. To ensure that this works, make sure your browser isn't blocking any cookies from Cloudinary.

![wefsef]( "wefwef")

![Netlify CMS integration](https://res.cloudinary.com/artisanstatic/cloudinary.png)