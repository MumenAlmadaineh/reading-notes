# Using chart.js to Create Animated Charts

![Controlling size of images in CSS Photo](https://user-images.githubusercontent.com/1479100/45607189-2b018b80-ba7d-11e8-845e-d7ab810bc07f.png)

## What is the Chart.js?

Chart.js is a free open-source JavaScript library for data visualization, which supports 8 chart types: bar, line, area, pie (doughnut), bubble, radar, polar, and scatter.

## How We Can start with Chart.js?

Setting up:

- The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
    <body>
    </body>
</html>
```

## How We can drawing with chart.js?

You can start drawing inside the chart.js by writing the code, for example

`<canvas id="buyers" width="600" height="400"></canvas>`

This line of code will Draw a line chart

- Then we have to write a script that will retrieve the context of the canvas

```
<script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
</script>
```

This part of the code we need to add it to the foot of our body element:

# From where We can installing Chart.js

We can install the latest version of Chart.js from three different sources

1. [npmjs.com](https://www.npmjs.com/package/chart.js)

2. [github.com](https://github.com/chartjs/Chart.js/releases/tag/v3.5.0)

3. [jsdelivr.com](https://www.jsdelivr.com/package/npm/chart.js)

![Aligning images in CSS Photo](https://nordicapis.com/wp-content/uploads/API-model-canvas-developer-experience.png)

### This is the beginning of the simple steps to start using chart.js. If you want to learn more, you can watch the video below

[Getting Started With Chart.js](https://www.google.jo/url?sa=t&rct=j&q=&esrc=s&source=video&cd=&cad=rja&uact=8&ved=2ahUKEwje7_nYlqPyAhUPhVwKHT_EB3EQtwJ6BAgFEAM&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DsE08f4iuOhA&usg=AOvVaw2Tk0n32OG6aYv_rMOSiS8e)
