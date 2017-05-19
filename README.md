# A-Frame How-To Guide
<img src = "https://upload.wikimedia.org/wikipedia/commons/8/86/Manproposesgoddisposes.jpg">

## Introduction to WebGL and A-Frame

The **Web Graphics Library** (WebGL) is a JavaScript framework for displaying 2D and 3D graphics in a browser.
**Mozilla A-Frame** is built on top of WebGL to make it easy to create and share content by making customized HTML elements.
A-Frame makes it possible to develop for **virtual reality** (VR) in 3D for free using just the browser.
No need to buy an expensive VR headset or subscribe to any development environment!

Further reading: 

[Building up a basic demo with A-Frame - Game development | MDN](https://developer.mozilla.org/en-US/docs/Games/Techniques/3D_on_the_web/Building_up_a_basic_demo_with_A-Frame)

[Dev.Opera — An Introduction to WebGL — Part 1](https://dev.opera.com/articles/introduction-to-webgl-part-1/#implementations)

## Make a scene in your browser!

It's easy to look at the initial concepts of using primitive shapes and 2D texture image files by using this [starter example](https://glitch.com/~aframe). This will create an HTML document that you can edit with the A-Frame library src and `<a-scene>` element set up for you. While you are exploring the various A-Frame examples and community content for inspiration, look at the source code in the inspector by pressing `ctrl + alt + i`.

## Primitives and Textures

A primitive is a simplified `<a-entity>` HTML element that A-Frame will generate for you. Three features make them easier to use than an `<a-entity>`component: 

1. They have special names like "plane" and "sky". 

2. Some of their properties (geometry and material) are preset with default values.

3. When you declare one, you can use HTML attributes to specify component properties.

### Try it out, add a primitive and texture of your own!
All primitive shapes have a position, scale and orientation in 3D space. You can add them into the `<a-scene>` element by typing `<a-name position="# # #"></a-name>` where name is the primitive type you want to add and # are the coordinates where you want to add it. Remember to add an offset, so that your primitive elements won't all be right on top of one another at the origin! Try experimenting with some different shapes and scales!

To add a texture, you first need to host the image file somewhere accessible. If you're using Glitch, just upload it to the assets page. Then add a `src=` attribute to the HTML element and include the URL to the image. The image will load as the texture.

Further reading:

[HTML & Primitives – A-Frame](https://aframe.io/docs/0.5.0/introduction/html-and-primitives.html)

## The Mozilla A-Frame Component Registry
The [A-Frame Registry](https://aframe.io/aframe-registry/) has components written by the community that you can include and edit to make something new and cool. Copy the JS link and include it in a `<script>` tag in your HTML file. Now your `<a-entity>` elements have a new attribute that you can specify! 

### An example of


Further reading:

To explore even more components, spend some time on [the Awesome A-Frame GitHub site](https://github.com/aframevr/awesome-aframe). 

When you've ready to learn the details of how it works, start by reading the official documentation [for a component here](https://aframe.io/docs/0.5.0/core/component.html).

Once you know what a component is and start thinking about [writing a component of your own, go here](https://aframe.io/docs/0.5.0/introduction/writing-a-component.html).


## Using glTF and Clara.io

Further reading:

[Troubleshooting and Optimizing 3D Models for A-Frame - Jared Pike](https://dev.opera.com/articles/introduction-to-webgl-part-1/#implementations)

## Using Javascript and DOM APIs
