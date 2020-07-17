<h1> READING NOTES</h1>
  <h2>HTML & CSS // JON DUCKETT</h2>  
    <h3> Chapter 7: Forms</h3>
      <ul>
        <li>Inputs, radio buttons, checkboxes, drop-down, etc.
        <li> Form: user enters info, clicks a button, name of form control is sent to the server with user input, server processes info, surver creates new page and sends it back to the browser.
        <li>< form> that contains an ACTION (the url for where on the server the info is going), sometimes a METHOD and ID
        <li>text input uses the < input> element which uses type="text" or "number", name and can also use min/max length
        <li>can create a password input using < input type="password">
        <li>< textarea> creates a multi-line text input using cols="20" and rows="4" or however big you want it
        <li>< input type="radio"> creates radio buttons and uses name, value (which is the value sent to the server if the button is checked), and checked (which indicates that this button should be checked when the page loads)
        <li>< input type="checkbox">creates checkboxes that can be used to indicate more than one thing and use name, value and checked just like radio buttons
        <li>drop down lists can be created using < select> and take a name
        <li>options on the drop down menu are created using < option> and takes a value which is the option that appears on the list and is also what is sent to the server
        <li>to allow users to select more than one thing on the drop down, use multiple="multiple"
        <li>if you want people to upload a file use < input type="file">
       <li>or a submit button use < input type ="submit"> the value will be the text that appears on the button
        <li>to make an image be the submit button use < input type="image">
        <li>each form control should have a <label> element with it
        <li>can either wrap the form control or be seperate from it and use the for attribute: <label for="cat input">Input your cat here!</label>
        <li>to group form elements you can use <fieldset> which groups the elements together with a line around the edge and then <legend> which comes directly after the fieldset tag and contains a caption which helps id the purpose of that group of form controls
        <li>can also specify type of info to be input like date, email, url
        <li>type="search"makes a specific search input and placeholder allows you to have text in that search area until someone types something in it

<h3> Chapter 14 : Lists, Tables, and Forms</h3>
      <ul>
        <li>in CSS, the list-style-type property allows you to control the shape of the bullet point in an unordered list
        <li>can use none, disc, circle, square
        <li>in an ordered list, it can be used to specify as well
        <li>decimal (number), decimal-leading-zero (number with a zero in front), lower-alpha (lower case letters), upper-alpha, lower-roman and upper-roman
        <li>can also make images into bullets with list-style-image: url(the url of the image here)
        <li>list-style-position lets you specify if the marker is contained inside or outside of the box containing the list
        <li>there are lots of different table properties
        <li>buttons, text inputs, fieldsets, ledgends can all be styled

<h1> READING NOTES</h1>
  <h2>JAVASCRIPT & JQUERY // JON DUCKETT</h2>  
    <h3> Chapter 6: Events</h3>
      <ul>
        <li>several outdated ways to do handle events, best practice is using event listeners with addEventListener()
        <li>older versions of internet explorer are not always great with event listeners
        <li>the flow of your code matters with event listeners because if things are nested within it, they have an order to the way they will happen
        <li>load is an event that is used to trigger scripts
        <li>focus and blur are triggered when dom elements come into or out of focus
        <li> click is triggered when something is clicked
        <li>event listeners can also be used to show position of the mouse when something was clicked, or record which key was pressed