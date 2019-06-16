---
section_number: 3
section_title: Setting up the slideshow

---

I opted for a background slideshow for the header of the site. This conistsed of 5 different images from the Polytech and Project.

I found this CSS based slideshow on the CodeDrops website and decided to base mine off of it.
![Site Animation](slideshow.PNG)

The slideshow also came with documentation which made it easy to implement as it addressed each part of the code.

As there was a fair amount of code to quickly summarise the process I used an unordered list for the slideshow and added a span for each image and a division with a heading. The spans are the elements that hold background images of the slideshow.

<script src="https://snipsave.com/embed/3fWc42P0Ic38nITkJw.js"></script>

The span that will contain a slideshow image will be positioned absolutely and have a width and height of 100%. The background-size property value “cover” makes sure that the background image covers all the area of the element and hence it is the size of the screen, it will cover all the visible viewport. The opacity is set to 0. here but is changed in our animation.

<script src="https://snipsave.com/embed/CWgQCkvDXX39LP0eVX.js"></script>

The animation for each span lasts 36 seconds and run an inifinite number of times.

<script src="https://snipsave.com/embed/Gx6pB1faf4294OSKbf.js"></script>

Finally here's a look at how I defined the background images for all the spans and the animation delay. Each following slideshow image and title appear after 6 seconds of the previous one:

<script src="https://snipsave.com/embed/oHL10dfXXzUfdYf23Z.js"></script>

![Site Animation](theanimation.PNG)
