<!-- From the Duckett HTML book:

Chapter 2: “Text” (pp.40-61)
Chapter 10: Ch.10 “Introducing CSS” (pp.226-245)
From the Duckett JS book:

Chapter 2: “Basic JavaScript Instructions” (pp.53-84)
Chapter 4: “Decisions and Loops” only up to the section on switch statements (pp.145-162) -->

<h1> READING NOTES</h1>
  <h2>HTML & CSS // JON DUCKETT</h2>  
    <h3> Chapter 2: Text</h3>
      <ul>
         <li> When creating a web page, you add tags (called markup) to the contents of the page, which provide meaning & allow browsers to show users the appropriate structure for the page.
         <li><strong>Structural Markup</strong> are the elements that you can use to describe both headings & paragraphs. 
         <li><strong>Semantic Markup</strong> provides extra info, such as where emphasis is placed in a sentence, quotes, etc.
         <li>There are 6 levels of headings, displaying in progressively smaller sizes as numbers get higher.
         <li>< p> tags are for paragraphs.
         <li>< b> is for bold and < i > is for italic.
         <li>Superscript (eg the th in "4<sup>th</sup>") is < sup>
         <li>Subscript (eg the 2 in CO<sub>2</sub>) is < sub>
         <li>White space collapsing: even when more than one space or paragraph is coded, the browser will only read it as one space.
         <li>Line breaks are < br /> and horizontal rules (which create a break between themes) are < hr /> as below:
         <hr />
         <li>White space and line breaks are <strong>empty elements</strong> which ususally only have one tag.
         <li>Visual editors and code views are often both included in Content Management Systems (CMS).
         <li><strong>Semantic Markup</strong> add extra information to pages.
         <li>< strong> and < em> will by default act like bold and italics, respectively. 
         <li>< blockquote> is for longer quotes and < q> is for shorter quotes. 
         <li> < abbr> will work for abbreviations and acronyms. (eg <abbr title="Professor">Prof</abbr>)
         <li>< cite> will cite a work in proper formation (make book titles italics)
         <li>< dfn> is to show the defining instance of a new term. 
         <li>< address> contains contact details (eg email address)
         <li>< ins> and < del> can be used to show visible insertion or deletion of content.
         <li> < s> indicates that something is no longer accurate (eg striking out an out-of-date price of computer)
        </ul>

<h3> Chapter 10: Introducing CSS</h3>
    <ul>
        <li> CSS makes web pages more attractive. 
        <li> Imagine every HTML element in its own box.
        <li> CSS creates rules related to each specific box.
        <li> Block and Inline elements are applicable here too.
        <li> CSS rules contain two parts: a SELECTOR (indicates which element the rule applies to) and a DECLARATION (how it should be styled).
        <li> PROPERTIES indicate the aspects to be changed. VALUES specify the setting you want to use (eg a color for text)
        <li>Using external CSS is possible with < link> in the HTML document & <strong>href</strong> (specifies the path to the CSS file), <strong>type</strong> (specifies the type of doc being linked to-- should be text/css) and <strong>rel</strong> (the relationship between the HTML page and the file it is linked to).
        <li> < style> will also allow CSS styling in an HTML document, weirdly, without needing to link to a .css file.
        <li> CSS selectors: universal selector (applies to all elements) | type selectors (matches element names) | class selector ( . ) | ID selector ( #) | child selector (matches an element that is a direct child of another) eg: li>a targets any a elements that are a child of li | descendant selector targets elements within a tag even if not a direct child( p) | adjacent sibling detector eg: (h1 + p) targets the first p element after any h1 | general sibling selector eg: h1~p {} finds multiple p elements that are siblings of an h1.
        <li>CSS rules CASCADE. 
        <li>Last rule generally wins, but also more specific rules win. 
        <li>You can put !important next to something later to make it more important than other rules. It will win.
        <li>INHERITANCE of values is possible within same tag. eg padding: inherit for an element to be the same as the above in a tag.
    </ul>

<h2>JAVASCRIPT & JQUERY // JON DUCKETT</h2>  
    <h3> Chapter 2: Basic Javascript Instructions</h3>
      <ul>
        <li>Statements: individual instructions/steps in a script. Should end with ;
        <li>{ these braces indicate the start and end of a code block}
        <li> JavaScript is case-sensi. 
        <li> You should write comments to explain what your code does. (multi-line with /* at beginning and end */ and // for single line)
        <li> Variable: allow scripts to store temporary bits of data. 
        <li>Data stored in a variable can change any time a script is run.
        <li>Assign value with =
        <li> Data types: numeric, string, boolean.
        <li> Scripts contain very precise instructions, eg specify that a value must be remembered before creating a calculation using that value.
        <li>Arrays are special types of variables, more than one piece of info stored.
        <li> Expressions evaluate into a single value.
        <li> Expressions rely on operators to calculate a value.
      </ul> 
     <h3>Chapter 4: Decisions and Loops</h3>
      <ul>
        <li>Conditional statements allow your code to make decisions about what to do next.
        <li> Comparison operators ( === !=== == < > <= =>) are used to compare 2 operands. 
        <li> Logical operators allow you to combine more than one set of comparison operators. 
        <li> if..else statements allow you to run one set of code if a condition is true, another if false
        <li> SWitch statements allow you to compare a value against possible outcomes (and also provides a default option if none match).
        <li> Data types can be coerced from one type to another. 
        <li> All values evaluate to either truthy or FALSY. 
        <li> There are three types of loop: for, while, and do...while. Each repeats a set of statements. 
        </ul>