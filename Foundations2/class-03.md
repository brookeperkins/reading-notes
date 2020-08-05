## Responsive Web Design

https://learn.shayhowe.com/advanced-html-css/responsive-web-design/

<ul>
<li>responsive web design: the website looks good AND works on every device and screen
<li>three main components
    <li> FLEXIBLE LAYOUTS
        <li>use a flexible grid that dynamically resizes (uses em units or percentages)
    <li> MEDIA QUERIES
        <li>specify different styles for individual browser and devices
        <li>can do this using @media or @import
        <li>have three logical operators: and, not and only
        <li>can also specify resolution, orientation, aspect-ratio and height/width
        <li>can also use viewport to help display on mobile devices
    <li> FLEXIBLE MEDIA
        <li>can make media (img, video, canvas, etc) flexible by using max-width: 100%
        <li>max-width doesn't work with iframes
</ul>

## All About Floats

https://css-tricks.com/all-about-floats/
<ul>
<li>floats are fragile!
<li>float is a CSS positioning property!
<li>floated elements remain a part of the flow of the web page!
<li>can be used for complete layouts in smaller instances
<li>the sister property of float is clear which, when placed on an element, allows it to remove itself from the flow of the other floated items and remain below them
<li> Beware of the "collapsed" parent element if only floats are the children
<li>has four values: both, left, right and none
</ul>

## Don't overthink it GRIDS

https://css-tricks.com/dont-overthink-it-grids/

<ul>
<li>Many sites use grid
<li>Wrapper div for grid set to width: auto
<li>Columns can be floated. Can set class names to ".col-1-2" etc. And set those to width: %
<li>Clear
<li>Gutters can be tricky
<li>Use box-sizing: border-box so width is not impacted by padding and borders
</ul>

## CSS FLOATS Explained

https://www.freecodecamp.org/news/css-floats-explained-by-riding-an-escalator-57fa55232333/

<ul>
<li>Floats create alternate flows: normal, left, right 
<li>Floats create new relationships between flows
<li>Clear: left align behind the first element that is floated left 
<li>clear: both escalator example, person takes up both sides of the escalator because there is a suitcase
</ul>