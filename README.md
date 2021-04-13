# VIEW Justin Murdock's Blog: [MurdockFPV](https://murdockfpv.github.io/)

Justin Murdock (owner, author)

[create your own](https://howchoo.com/git/how-to-blog-in-markdown-using-github-and-jekyll-now) blog ([fork this](https://github.com/barryclark/jekyll-now))

___

# Blog to serve as a portfolio for my drone photos

## Documentation:

### 360 Photo-viewer usage: 

* code example: https://github.com/murdockfpv/murdockfpv.github.io/blob/master/_posts/2021-01-11-photosphere_vr.md
* demo: https://murdockfpv.github.io/vrphotos/

```
{% include PHOTOSPHERE_LIBRARY.html %}
{% include PHOTOSPHERE.html caption="Shasta Lake, California" img_url="/images/2021-04-09/DJI_0379.JPG" id="viewerA" default_lat="-0.3" default_long="1.3" default_zoom="20" %}
```

### 360 Photo-viewer with flipbook ability:

* code usage example: https://github.com/murdockfpv/murdockfpv.github.io/blob/master/2021-02-09-vrclouds.md
* demo: https://murdockfpv.github.io/vrclouds/

### how to getPosition() from the 360 viewer (to find values to set the initial latitude and longitude)

> console -> `viewerA.getPosition()`

### Affiliate link with image preview:

```
{% include image.html img_url="https://github.com/murdockfpv/murdockfpv.github.io/blob/master/images/list-2021-01-03/4_taranis_x9d.jpg?raw=true" description="$218 FPV CONTROLLER: Taranis X9D" product_aff_link="https://www.amazon.com/FrSky-Taranis-Access-Telemetry-Silver/dp/B07VRP1V76/ref=sr_1_1?tag=juliusakula-20" %}
```

### Posting videos:

* code example: https://github.com/murdockfpv/murdockfpv.github.io/blob/master/vid_test.md
* demo: https://murdockfpv.github.io/vid_test/

