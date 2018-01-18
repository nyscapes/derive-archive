---
title: How to Post a Dérive
author: mds17 
map: true
derive:
  - [40.731035, -73.997506]
  - [40.730636, -73.997152]
  - [40.729002, -73.993784]
  - [40.728449, -73.994245]
  - [40.727124, -73.991616]
  - [40.725660, -73.992131]
  - [40.723920, -73.987947]
  - [40.724603, -73.987486]
  - [40.725612, -73.989878]
  - [40.724319, -73.990812]
  - [40.724912, -73.992303]
  - [40.722823, -73.993033]
---

Posting a dérive to this archive is the same exact process as posting to our
Media Blog, in which case you should start by reminding yourself of the
[process for posting to the Media
Blog](https://nyscapes.github.io/media-history-blog/2018/01/12/how-to-post-to-this-blog.html).
There is one significant addition, however, which is the result of each
dérive’s including a map that indicates the path you’ve taken while on your
dérive. The first two steps for making the map are straightforward:

1. Go on the dérive and trace your path on your [Field Papers
   atlas](http://fieldpapers.org/compose#14/40.7220/-73.9924).
1. Convert every turn you make into a point by finding its coordinates using
   [LatLong](https://www.latlong.net/), which lets you click on the map and
   get the coordinates. Keep track of every vertex.

The final step gets a bit trickier and involves the post’s metadata. First,
you have to let the blogging software know that there should be a map. Do this
by adding `map: true` to the metadata. 

Next, once you have each vertex (turning point) recorded, in order, you want
to place them in a special metadata field called `derive`. For example, for the
map you see in this post, the metadata is:

```
---
title: How to Post a Dérive
author: mds17 
map: true
derive:
  - [40.731035, -73.997506]
  - [40.730636, -73.997152]
  - [40.729002, -73.993784]
  - [40.728449, -73.994245]
  - [40.727124, -73.991616]
  - [40.725660, -73.992131]
  - [40.723920, -73.987947]
  - [40.724603, -73.987486]
  - [40.725612, -73.989878]
  - [40.724319, -73.990812]
  - [40.724912, -73.992303]
  - [40.722823, -73.993033]
---
```

Then the blogging software will automatically convert that `derive` metadata
into a path on the map. Note carefully the syntax:
  
  * Every vertex is introduced by two spaces and a hyphen: <code>&nbsp;&nbsp;-</code>.
  * Every vertex is has the latitude first (around 40.7) and the longitude
    second (around -74.0).
  * Every vertex is surrounded by `[]` brackets.
  * The latitude and longitude are separated by commas.
