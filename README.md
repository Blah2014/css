# css
CSS related stuff

***Please donate if you are using this repo***

***Note:*** If you found this project helpful please give this repo a star.

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=C2HFZWSUPV47Q" target="_blank">
  <img src="https://raw.githubusercontent.com/Blah2014/phonegap-inmobi-plugin/gh-pages/images/BuymeaCoffee.png" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!" />
</a>

<a href="http://traderhub.info" target="_blank">
  <img src="http://traderhub.info/images/AD.jpg" border="0" name="submit" alt="TraderHub - daily stock picks, market signals, stock picking service" />
</a>

### Index
* [inspiration](#user-content-inspiration)

* [Best free stock photos in one place](#user-content-best-free-stock-photos-in-one-place)

* [CSS features you should use](#user-content-css-features-you-should-use)

### inspiration
[dribbble.com](https://dribbble.com/)

### Best free stock photos in one place
[pexels.com](https://www.pexels.com/)

### CSS features you should use
```css
::before and ::after

/* box-sizing */
* {
  /* The width and height properties (and min/max properties) includes content, padding and border, but not the margin */
  box-sizing: border-box;
}

/* flex */
display: flex;

-webkit-flex: 1; /* Safari 6.1+ */
-ms-flex: 1; /* IE 10 */ 
flex: 1;

flex-direction: row | row-reverse | column | column-reverse | initial

/* justify-content */
justify-content: flex-start|flex-end|center|space-between|space-around|initial|inherit;

/* Vertical Centering */
With Flexbox, you can stop worrying. You can align anything (vertically or horizontally) quite painlessly with the align-items, align-self, and justify-content properties.

/*  will-change */
/* Keyword values */
will-change: auto;
will-change: scroll-position;
will-change: contents;
will-change: transform;        /* Example of <custom-ident> */
will-change: opacity;          /* Example of <custom-ident> */
will-change: left, top;        /* Example of two <animateable-feature> */

/* Global values */
will-change: inherit;
will-change: initial;
will-change: unset;

/* CSS3 Multi-column Layout */
div {
    -webkit-column-count: 3; /* Chrome, Safari, Opera */
    -moz-column-count: 3; /* Firefox */
    column-count: 3;
}

/* text-overflow */
p {
    width: 200px;
    padding: 4px;
    border: 1px solid black;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}

/* rgba */
.red{
  background-color: rgba(255, 0, 0, 0.5);
}

/* Width and Height */
px - Pixels.
em - A unit of measurement, where 1 em = current font size.
rem - Root em. Same measurement as em, but makes life much easier without the inheritance problem
% - Percentages.
auto - highly useful unit, will explain below

/* margin */
margin: 20px 10px 20px; /* This refers to Top, Left and Right, Bottom */
margin: 0 auto; /* Margins with auto on the left and right are used to center an element with a display value of block */


```
