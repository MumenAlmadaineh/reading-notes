# Controlling size of images in CSS

![Controlling size of images in CSS Photo](https://assets.codepen.io/17102/internal/screenshots/pens/obWdgp.default.png?fit=cover&format=auto&ha=false&height=540&quality=75&v=2&version=1452308065&width=960)

CSS gives us the ability to change pictures size in our website by using some of the properties inside CSS for example :

```
img {
  width: 100%;
  height: auto;
}
```

this code will give fill size to the image in the web page.

# Aligning images in CSS:

![Aligning images in CSS Photo](https://user.oc-static.com/upload/2018/06/14/15289918022085_1.png)

Align Images refers to how images arrange inside our web page and this happens by using more than one property for example to place Images Side by Side:

> 1. (w3schools) Add HTML:
```
<div class="row">
  <div class="column">
    <img src="img_snow.jpg" alt="Snow" style="width:100%">
  </div>
  <div class="column">
    <img src="img_forest.jpg" alt="Forest" style="width:100%">
  </div>
  <div class="column">
    <img src="img_mountains.jpg" alt="Mountains" style="width:100%">
  </div>
</div>
```

> 2. (w3schools) Add CSS::
```
/* Three image containers (use 25% for four, and 50% for two, etc) */
.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: table;
}
```

> (w3schools) How to create side-by-side images with the CSS flex property:

```
.row {
  display: flex;
}

.column {
  flex: 33.33%;
  padding: 5px;
}
```

# Adding background images

In HTML we can change the pictures background by using some CSS property for example:

```
body  {
  background-image: url("https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/Dark-brown-solid-color-background.jpg/2560px-Dark-brown-solid-color-background.jpg");
 color: #1565C0;
}
```
this code in CSS will give web page body brown background and blue text color

[If you want read more visit w3schools website](https://www.w3schools.com/cssref/pr_background-image.asp)

#  Search engine optimization

![Search engine optimization Photo](https://www.thebalancesmb.com/thmb/3tO0sKMbIm2FFg7Vc6dnuGwgVV4=/4952x2991/filters:fill(auto,1)/seo-search-engine-optimization-concept-644911062-5ae3efdd04d1cf003cf95b58.jpg)

If I will explain this term by simply way I can I will say it means how search engines can read your content on your website

So there are some steps we need to do to show our website in the first result in search engines like Google for example using analytics to understand visitors

![Search engine optimization Photo](https://philosophycommunication.com/wp-content/uploads/2020/04/googleanalytics_websitevisitors_1.png)

And of course, we need to put your site on the web Otherwise, how will search engines read your content if it is offline we can make our website online by using something its name 'Domain Names & Hosting'

![Domain Names & Hosting Photo](https://themegrill.com/blog/wp-content/uploads/2020/07/DNS-Server1.jpg)

[godaddy it's beast website you can lrean about Domain Names & Hosting](https://uk.godaddy.com/)

# additional information if you want read more it's about software it's name it's Adobe Flash Player :

![Adobe Flash Playe Photo](https://www.kodaweb.co.nz/sites/default/files/Flash_0.png)

> (Adobe) Adobe Flash Player EOL General Information Page

Since Adobe no longer supports Flash Player after December 31, 2020 and blocked Flash content from running in Flash Player beginning January 12, 2021, Adobe strongly recommends all users immediately uninstall Flash Player to help protect their systems.  

Some users may continue to see reminders from Adobe to uninstall Flash Player from their system.  See below for more details on how to uninstall Flash Player.