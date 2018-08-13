---
layout: post
title: 'timelapse stacking'
---

An ongoing project to compress a timelapse into one image using various filters like Numpy median, std, var and so forth.

The project seeks to be able to use distributed computing to solve the issue and therefore all images are tiles up so to save on memory and therefore be able to run on raspberry pi's.

The [repo](https://github.com/sloev/timelapse_stacking) contains a jupyter notebook with all the necesary code.

Here is the output documented from a std flattening:
{% include image.html image="projects/timelapse_stacking/thumb.jpg" %}

Clone the repo [here](https://github.com/sloev/timelapse_stacking).
