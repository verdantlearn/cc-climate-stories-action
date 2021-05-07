---
title: Course-in-a-Box Cheatsheet
---

## Modules
To add a new module, create a new folder within the `modules` folder, and within that a folder called `_posts`.  Add new .md files using the usual Jekyll naming convention 

To list your new module in the top menu, add it to `_data/course.yml`



<br>

----
## Images


Centered image:
<center><img src="/img/preview-changes.png" alt="screenshot of github's Preview Changes function" width="75%"/></center>


<br>


----
#### Fancy Buttons

<a class="btn btn-primary" href="https://www.p2pu.org/en/"><i class="fa fa-home"></i> Join the conversation!</a>

<br>

## Media cheetsheat

While Markdown supports adding images, its capacities for media are generally limited. Fortunately, Markdown is designed to support and work alongside HTML, which has vast options for customizing your course content with images, videos, and other interactive features.

<br>

----
##### Using Existing Images
If you're using an image that is already uploaded somewhere, you can copy the URL and use it like in the example below:

```
![alt](https://www.p2pu.org/assets/images/p2pu-logo.png)
```

![alt text for image](https://www.p2pu.org/assets/images/p2pu-logo.png)

<br> 

----
##### Hosting Images on Github

You can also host images for your course for free through GitHub. Head to the `img` folder, click *Add File > Upload Files* (top right above the list of files), and use the upload tool to add your images. When you add an image to your course, you'll link to it with the code below and replace `logo.png` with the name of the image.

```
![alt]({{site.baseurl}}/img/logo.png)
```
![alt]({{site.baseurl}}/img/logo.png)

<br>

----
##### YouTube Videos
If you want to place a video in your course, the easiest way is to upload it to YouTube and grab the automatically-generated embed code from the **Share** button on the video's YouTube page. You can plop this directly into a submodule's `.md` file.

<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

```
<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```
<br>

----
#### CSS and styling

Hire a developer to make changes beyond the small edits I've made to adding VerdantLearn's two greens, and using the darker green occasionally

<br>
