---
layout: post
title:  "BarriosEnAcción (NeighborhoodsInAction)"
categories: colaborative platforms
img: image-2.png
categories: two
links: 
    - url: http://barriosenaccion.cl
      description: The running version
      type: link
    - url: github.com/ciudadanointeligente/barriosenaccion
      description: Repo in github
      type: github
---

BarriosEnAcción (NeighborhoodsInAction) is a reimplementation of the famous MySociety platform FixMyStreet. It was a cooperation between [Fundación Ciudadano Inteligente](http://ciudadanointeligente.org) and [CiudadViva](http://ciudadviva.cl) 
Use the guide to prepare good looking posts! The theme has a sidebar in the post layout which consists of post image, recent posts and facebook like box. This can be extended by editing the ``sidebar.html`` in **_includes** folder.

## Image

- Use image of ratio 400x250 (800x500). 
- Keep them inside ``images`` folder.
- Mention image name in the front matter as shown below

{% highlight yml %}
---
layout: post
title:  "Some title"
categories: some category
img: image-name.jpg
---
{% endhighlight %}