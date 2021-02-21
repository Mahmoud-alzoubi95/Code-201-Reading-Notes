# Reading-notes-201-class11
## From the Duckett HTML book:
+ **How to change image size in CSS?**<br> 
+ Sometimes, it is required to fit an image into a certain given dimension. We can resize the image by specifying the width and height of an image.
A common solution is to use the max-width: 100%; and height: auto; so that large images do not exceed the width of their container.
The max-width and max-height properties of CSS works better,
but they are not supported in many browsers.And You can control the size of an image using the width and height properties in CSS,
Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, 
and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.

+ The object-fit property is generally applied to image or video. This property defines how an element responds to the width and height of its container. Mainly there are five values of object-fit property such as fill, contain, cover, none, scale-down, initial, and inherit. The default value of this property is â€œfillâ€.


# How You Can Control of Width and Height Of An Image In Css?

- The width property specifies the width of an element, and the height property specifies the height of an element.
- The width and height of the image can be specified by applying these properties to the IMG element.


# Aligning images in CSS
> Rather than using the < img > elementâ€™s align attribute, web page authors are increasingly using the float property to align images. There are two ways that this is commonly achieved:

- The float property is added to the class that was created to represent the size of the image.

- New classes are created with names such as align-left or align-right to align the images to the left or right of the page. These class names are used in addition to classes that indicate the size of the image.
# Video and Audio
*You can review what all the HTML features do in the article linked above; for our purposes here, the most interesting attribute is controls, which enables the default set of playback controls. If you don't specify this, you get no playback controls.*

> It is a good idea to always include `width` and `height` attributes. If height and width are not set, the page might flicker while the video loads.
> The `<source>` element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.
> The text between the `<video>` and `</video>` tags will only be displayed in browsers that do not support the `<video>` element.
