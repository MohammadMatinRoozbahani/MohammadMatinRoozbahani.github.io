---
layout: page
title: Adventure in Nature
description: A project showcasing a fun outdoor adventure.
img: assets/img/nature-background.jpg
importance: 2
category: fun
---

Every project has a beautiful feature showcase page. 
It's easy to include images in a flexible 3-column grid format. 
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/adventure1.jpg" title="Hiking in the Mountains" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/adventure2.jpg" title="Camping Under the Stars" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/adventure3.jpg" title="Kayaking in the Lake" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Capturing the beauty of nature: on the left, hiking in the mountains; in the middle, camping under the stars; on the right, kayaking in the serene lake.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/adventure4.jpg" title="Wildlife Watching" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image shows the thrill of wildlife watching during our adventure.
</div>

<p>
    Our adventure in nature was filled with excitement and unforgettable moments. We explored breathtaking landscapes, encountered wildlife, and enjoyed the tranquility of the great outdoors. Each experience reminded us of the beauty and serenity that nature offers.
</p>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/adventure5.jpg" title="Group Photo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/adventure6.jpg" title="Sunset View" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A group photo to remember the adventure and a stunning sunset view to cap off the day.
</div>

<p>
    Nature has a way of bringing people together, and this adventure was no exception. We laughed, shared stories, and created memories that will last a lifetime. If you're looking for a fun outdoor experience, we highly recommend exploring the beauty of nature!
</p>
