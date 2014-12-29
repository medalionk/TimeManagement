
- Built on Bootstrap 3
- Fully Responsive
- Retina Ready
- Parallax Scroll
- CSS3 Animations
- Google Web Fonts

##Contents
1. HTML files
2. CSS files
3. Javascript files
4. Adding your screens
5. Using the icon set

##1. HTML files

The template has one HTML page where all the content for the site is housed:

```
index.html

```

The above code would give you 2 columns that sit side-byside on the page, each taking up half the page.

##2. CSS files

The theme has various CSS ﬁles, many of which you probably wont touch, but here is an overview of each one:

**iconfont.css** - This ﬁle controls the styling for the icon pack

**bootstrap.min.css** - This is the css framework provided by Bootstrap and includes the basic styling for the page (grid etc) and all the styles related to the framework itself.

**animate.min.css** - This includes the styling of the Daniel Edenʼs CSS3 
animation library Animate.css. Animations are triggered via Javascript in the 
scripts.js ﬁle.

**style.css** - This is the main style ﬁle that includes the styling for all the visual 
elements in the template.

##3. Javascript Files
As with the CSS ﬁles, you probably wont edit most of the Javascript ﬁles. Here is an overview:

**jquery.js** -

**retina.min.js** - The javascript to serve high-resolution images to devices with retina displays. To provide the retina version of a an image, create an image twice the size of the original, and then just add @2x to the same ﬁle name as shown below:

```
logo.png
logo@2x.png
```

**bootstrap.min.js** - The javascript provided by Bootstrap as part of the framework.

**animatescroll.js** - Provides smooth scrolling, to smooth-scroll to an element inside the page just use

```
<a onclick="$('[id-or-class-of-element]').animatescroll();">Go to Element</a>
```

**scripts.js** - This ﬁle is the main scripts ﬁle that controls all the pretty features of the template such as the the CSS3 animations. It also controls the mobile menu toggle and slider initializations.



