<h1> READING NOTES</h1>
  <h2>EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS</h2>
    <h3>https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js </h3>
       <ul>
        <li>Chart JS is a JS plugin used for creating animated charts. 
        <li>Uses canvas in HTML5.
        <li>Steps: Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in, then create new HTML page and import the script. It should look like this:
        </ul>

    <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="utf-8" />
            <title>Chart.js demo</title>
            <script src='Chart.min.js'></script>
        </head>
        <body>
        </body>
    </html>
<ul>
    <li>Be sure to have a <canvas> in HTML doc.
    <li>Can do pie, bar, and line chart.
</ul>

<h2>Chart.js</h2>
<h3>https://www.chartjs.org/docs/latest/</h3>
<ul>
<li>Includes all docs about Chart.js
<li>Installed - 'OK' to render a chart, then you need < script> and a < canvas> element.

<h2>Basic usage of canvas</h2>
<h3>https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage</h3>

    <canvas id="tutorial" width="150" height="150"></canvas>

</ul>
<ul>
<li>No src or alt attributes. 
<li>If no width or height is specified, default measurements will be 300px wide x 150px high.
<li>Can add fallback content inside the canvas tags incase the browser does not support canvas.
<li>Canvas is initially blank, needs script to render context and draw on it. 
<li>Get the node using getElementById, then getContext(). 
<li>For 2D graphics, use "2d":

    var canvas = document.getElementById('tutorial');
    var ctx = canvas.getContext('2d');

</ul>
<ul>
<li>Backup option if it's not available:

    var canvas = document.getElementById('tutorial');

    if (canvas.getContext) {
    var ctx = canvas.getContext('2d');
    // drawing code here
    } else {
    // canvas-unsupported code here
    }
</ul>

<h2>Drawing Shapes with Canvas<h2>
<h3>https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes</h3>
<ul>
<li>Drawing with Canvas: one unit on the grid is usually 1px. 
<li>Canvas only supports RECTANGLES, and PATHS (list of points connected by lines). 
<li>Using Canvas options, you can draw triangles, hearts, circles, squares, etc etc.
<li>Drawing a rectangle: filled rectangle fillRect(x, y, width, height) - rectangle outline strokeRect(x, y, width, height) - clear transparent rectangle area clearRect(x, y, width, height)
<li>Path methods: There are various drawing paths - beginPath() - closePath() - stroke() - fill() - moveTo() - lineTo() - etc.
<li>Sideways triangle example:

    function draw() {
    var canvas = document.getElementById('canvas');
    if (canvas.getContext) {
        var ctx = canvas.getContext('2d');

        ctx.beginPath();
        ctx.moveTo(75, 50);
        ctx.lineTo(100, 75);
        ctx.lineTo(100, 25);
        ctx.fill();
      }
    }
</ul>

<h2>Applying Styles and Colors<h2>
<h3>https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors</h3>

<ul>
<li>Colors, line styles, gradients, patterns, and shadows!
<li>COLORS Can fillStyle = color and color can be a name, RBG(A), or HEX values. 
<li>Can set a ctx.globalAlpha = 0.2 meaning all the shapes after this is set will have that transparency value.
<li>LINES can control line properties like lineWidth = value and getLineDash(). 
<li>Line width default is 1.0 units. 
<li>Can use for loops when drawing. 
<li>This is useful for moving the pen around the pixels (which would be [i]). 
<li>Line cap are the end points of the line. 
<li>Can make zigzag lines.
<li>Line cap: BUTT squares off the endpointsround ROUND rounds the end points SQUARE squares the endpoints.
<li>GRADIENTS Can create linear and radial gradients. 
<li>Can create patterns too by repeating a design or img.
<li>SHADOWS Can use shadows to add shadow to text too!
</ul>

<h2>Drawing Text</h2>
<h3>https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text</h3>

<ul>
<li>fillText used to make solid text:
</ul>
    //solid "Hello world"
    function draw() {
    var ctx = document.getElementById('canvas').getContext('2d');
    ctx.font = '48px serif';
    ctx.fillText('Hello world', 10, 50);
    }
    strokeText to outline text

    //outline "Hello world".
    function draw() {
    var ctx = document.getElementById('canvas').getContext('2d');
    ctx.font = '48px serif';
    ctx.strokeText('Hello world', 10, 50);
    }

<ul>
<li>Can use this to play with font, textAlign, textBaseline, and direction.
</ul>