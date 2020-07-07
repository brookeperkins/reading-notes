<!-- From the Duckett HTML book:

Introduction (pp.2-11)
HTML Chapter 1: “Structure” (pp.12-39)
HTML Chapter 8: “Extra Markup” (p.176-199)
HTML Chapter 17: “HTML5 Layout” (pp.428-451)
HTML Chapter 18: “Process & Design” (pp.452-475)
From the Duckett JS book:

Introduction
JS Chapter 1: “The ABC of Programming” (pp.11-52) -->

<h1> READING NOTES</h1>
  <h2>HTML & CSS // JON DUCKETT</h2>  
    <h3> Chapter 1: Structure</h3>
      <ul>
         <li> HTML pages are text documents. </li>
         <li> HTML describes the structure of pages using <strong>elements</strong>.</li>
         <li> Elements are characters inside two tags: opening and closing, denoted with left- and right-angled brackets.</li>
         <li> Tags act like containers</li>
         <li> opening tags indicate that anything between the tags is HTML code.</li>
         <li> The < body > tags shown inside the main browser window.</li>
         <li> Headings and sub-headings include < h1 > through < h6> and their closing tags. </li>
         <li> Paragraph text appears between < p > < /p > tags.</li>
         <li> Attributes provide more info about elements and are made of of a <strong>name</strong> and a <strong>value</strong>.</li>
         <li> Name of Attribute: what kind of extra info is being supplied. </li>
         <li> Value of Attribute: the information or setting for the attribute.</li>
         <li> (eg: "lang= en-us") wherein lang is the name and en-us is the value.</li>
         <li> Body elements: everything inside is shown in the main browser window.</li>
         <li> Head elements: information ABOUT the website. Ususally contains a < title > element.</li>
         <li> Title elements: shown in top of browser.</li>
         <li> You can view source code of websites to see their HTML and other code.</li>
        </ul>

<h3> Chapter 8: Extra Markup</h3>
    <ul>
        <li> Most current version is HTML5, but older versions are still existent throughout the internet.</li>
        <li> For this reason, HTML docs start with DOCTYPE to signal to browsers which version is being used.</li>
        <li> You can add a comment that will not affect the code by using < ! -- comment here-- > </li>
        <li> Comments are good practice so subsequent coders can understand the code more easily. </li>
        <li> ID attribute: uniquely identifies a particular element from others on the page.</li>
        <li> ID is a <strong>global attribute</strong> because it can be used on any element.</li>
        <li> Class attribute: can identify several elements on a page at once. </li>
        <li> An element can belong to more than one class.</li>
        <li> Block elements: include < h1> < p> < li> elements, which will always appear to start on a new line.</li>
        <li> Inline elements: appear to continue on the same line as neighbor elements (eg: < a> < b> < em> and < img>)</li>
        <li> The < div> element groups a set of elements together in one block-level text. </li>
        <li> Can be assigned a class attribute, thus able to be stylized. </li>
        <li> The < span> element in an inline equivalent of the < div> element. </li>
        <li> Span can: contain a section of text when no other optiin makes sense; contain multiple inline elements.</li>
        <li> The < iframe> is like a little window cut into the page that reveals another page (eg Google Maps inlay).</li>
        <li> <strong>src heigh</strong> and <strong>width </strong> are required attributes for iframe.</li>
        <li> Also, <strong>seamless</strong> in HTML5: can be applied to an iframe where scrollbars are not desired. </li>
        <li> < meta> element: ususally inside < head> element, contains info about the webpage (description, keywords, robots aka search engines).</li>
        <li> Escape characters are used to include special characters in pages such as &lt, &gt, &amp, &quot, &cent, &divide, and &copy.</li>
    </ul>

<h3> Chapter 17: HTML5 Layout</h3>
    <ul>
        <li> Many of the old < div> elements are being replaced by more semantic HTML names (eg < header>, < aside>, and < article>). </li>
        <li> The < header> and < footer> elements can contain site name and copyright info, or each article can have its own pair of these.</li>
        <li> The < nav> element contains the major navigational bloxkws on the site. </li>
        <li> < article > elements act as a container for any section of a page that could stand alone or be sydnicated (eg individual article, blog entry, comment, forum post, any independent piece of content). </li>
        <li> These elements can be nested inside one another (eg blog, comment on blog)</li>
        <li> < aside> elements used inside an article element contain info related to the article but not essential to its overall meaning. </li>
        <li> < aside> elements used outside an article contain content related to the entire page.</li>
        <li> < section> elements group related content together and typically have their own headings. </li>
        <li> < hgroup> elements group together a set of one or more < h1> through < h6> elements so they're treated as one headline. Not super popular.</li>
        <li> < figure> and < fig caption> relate to images, videos, graphs, diagrams, code samples, and text that supports the main body of the article. 
        <li> You can section elements with < div> even with HTML5's movement away from div. </li>
        <li> To make older browsers understand HTML5, extra Javascript is needed. </li>
    </ul>

<h3> Chapter 18: HTML5 Layout</h3>
    <ul>
        <li> It's important to understand your target audience: who they are, why they would come to your site, what info they want, and when they'll return. </li>
        <li> Site maps allow planning and structu]re of a site. </li>
        <li> Wireframes allow organization of information that needs to go on each page. </li>
        <li> Visual hierarchy helps visitors understand what you are trying to tell them. </li>
        <li> You can differentiate between pieces of info by using size, color, and style! </li>
        <li> You can use grouping and similarity to help simplify the inf you present. </li>
    </ul>

  <h2>JAVASCRIPT & JQUERY // JON DUCKETT</h2>  
    <h3> Chapter 1: The ABC of Programming</h3>
    <h3> Sections 1A: What Is A Script and How Do I Create One?</h3>
      <ul>
         <li> A <strong>script</strong> is a series of instructions.
         <li> eg recipes, handbooks, manuals. 
         <li> A computer follows these instructions to achieve a goal. 
         <li> Each time the script runs, it might only use a subset of all the instructions.
         <li> These instructions must allow the computer to solve the task programmatically. 
         <li> To write a script: break down your goal into a series of tasks and then work our each step needed to complete that task (eg flowchart).
     </ul>
     <h3> Section 1B: How Do Computers Fit In With the World Around Them?</h3>
      <ul>
        <li> Computers create models of the world using data. 
        <li> In these models, objects represent physical things. Objects can have: properties that tell us about the object; methods that perform tasks using the properties of that object; events which are triggered when a user interacts with the computer.
        <li> Programmers can write code to say "When this event occurs, run THAT code."
        <li> Web browsers use HTML markup to create a model of the web page. Each element creates its own node (a kind of object).
        <li> To make web pages interactive, write code that uses the browser's model of the web page. 
      </ul>
      <h3> Section 1C: How Do I Write A Script For A Web Page?</h3>
      <ul>
        <li>Best practice is to keep JavaScript in its own JavaScript file. They are similarly text files (like HTML & CSS) but with .js extension.
        <li> The HTML < script> element is used in HTML pages to tell the browser to load the JS file ( like the < link> element can be used to load a CSS file). 
        <li> If you view the Source Code of a page in the browser, the JS will not have changed the HTML, because the script works with the model of the web page that the browser has created. </li>