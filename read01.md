# Read01

## Responsiveness

Nowadays, mobile phones are so advanced and people started to access web pages using them more often. Since the webpages can now be accessed through different screen sizes, it was vital to think of ways to make it comfortable and user friendly when accessed from smaller screens.

You can create a responsive website using three methods that are interrelated:

*Flexible Layouts*

1. *Flexible layouts* mean that instead of specifying width and height using the pixels, they are specified using the `percentages` and `em`. So it will be relative to the parent element and to the width of the screen.

However, there is a problem about this method; in some cases, the elements take percentages relative to the parent element so if the parent is not big enough, the children element won’t be readable. Hence, there are other components that are used to cover this problem.

*Media Queries*

2.Media queries are linked to the CSS files in multiple ways. 1.The @media rule inside of an existing style sheet. 2. linking to a separate style sheet from within the HTML document. 

Media queries have different types and they should be specified, some types are:

`all`

`screen`

`print`

`tv`

`braille`

When the type is not specified, the default type will be `screen`.

Not all of the queries are applied because they would result in true and false and will only be executed if the result is true.

**Logical Operators with Media Queries**

`and` it applies both of the media queries.

`not` it applies anything but not the one specified.

`only` it only applies this media quire.

Note: in some cases, the media queries are comma separated and that implies an `or` operator.

**Media Queries Features**

You can specify features like height and width, which specify a width other that the device’s features.

You can also choose the Orientation which is very important to mobile devices. It can be:

Landscape: the height is less that the width. 

Portrait: the width is less than the height.



**Mobile First**

This is called Mobile first because it is a flexible method that starts up with the styles for smaller devices and then are edited to fit the bigger ones and this is the best way to make is easy for mobile to display websites.

**Viewport**

You can specify the size, scale, and resolution of a viewport. 

In the head of the HTML file, the `meta` tag is used to identify the viewport as the default width and height of the device.

*Flexible Media*

Giving the media a `max-width` of 100% will make images, videos scalable, it changes their size when the size of the viewport changes.

## Floats

-The float property is used for print layouts where there is an image and a text wrapped around it.

-The float property now has a wider range of uses and it can be used to create an entire page layout.

-You can clear the float for other elements so they are not affected by it. Use: `clear: both`.

-When a container contains floated elements, it usually collapses and its height becomes zero but it can be fixed by clearing the float before the close of the container.


There are different techniques to *clear the float* of an element other than using clear: both property.

1.The Empty `div` Method

2.The Overflow Method

3.The Easy Clearing Method


### Problems with Floats:

1.Pushdown

2.Double Margin Bug

3.3px Jog

4.Bottom Margin Bug

## Grids

-Give the container a 100% width.

-Give its child elements width using percentages as well. 

-Clear the float from the parent so it’s not collapsed.

-We don’t need percentages for the gutters, we can give it `box-sizing: border-box` and then give the children padding-right.

## SMACSS 

SMACSS is a guide that has instructions for the best way to write CSS rule in different pages so it helps with organizing the code more.








 

