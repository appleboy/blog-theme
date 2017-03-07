---
title: Big Image Sample
subtitle: Using Multiple Images
date: 2017-03-07
tags: ["example", "bigimg"]
bigimg: [{src: "/img/triangle.jpg", desc: "Triangle"}, {src: "/img/sphere.jpg", desc: "Sphere"}, {src: "/img/hexagon.jpg", desc: "Hexagon"}]
---

The image banners at the top of the page are refered to as "bigimg" in this theme. They are optional, and one more more can be specified. If more than one is specified, the images rotate every 10 seconds. In the front matter, bigimgs are specified using an array of hashes.

<!--more-->

A single bigimg can be specified in the front matter by the following YAML:
```
bigimg: [{src: "/img/triangle.jpg", desc: "Triangle"}]
```

Multiple bigimgs can be specified in the front matter by the following YAML:
```
bigimg: [{src: "/img/triangle.jpg", desc: "Triangle"}, {src: "/img/sphere.jpg", desc: "Sphere"}, {src: "/img/hexagon.jpg", desc: "Hexagon"}]
```

Also note that the description field is optional, and images could instead be specified by:
```
bigimg: [{src: "/img/triangle.jpg"}, {src: "/img/sphere.jpg"}, {src: "/img/hexagon.jpg"}]
```