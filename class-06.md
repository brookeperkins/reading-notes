<!-- From the Duckett JS book

Chapter 3: “Object Literals” (pp.100-105)
Chapter 5: “Document Object Model” (pp.183-242) -->

<h1> READING NOTES</h1>
  <h2>JAVASCRIPT & JQUERY // JON DUCKETT</h2>  
    <h3> Chapter 3: Object Literals (pp 100-105)</h3>
      <ul>
        <li>Onjects group together a set of variables and functions to create a model of something you would recognize from the real world.
        <li>In an object, variables become known as PROPERTIES.
        <li>In an object, functions become known as METHODS.
        <li>Name and value within an object are known as a KEY.
        <li>Literal notation is the easiest way to create an object (we've mostly done this early on, it seems).
        <li>Dot notation and square brackets are also useful (look cleaner?)
        <li> Eg: var hotelName = hotel.name ; var hotelName = hotel['name']
        <li>"Object literals" when listed out
        <li>Constructor Notation: the new keyword and the object constructor create a blank object to which you can add properties or methods.
        <li> eg: var hotel = newObject(); hotel.name = 'Quay'; hotel.rooms = 40 etc
        <li>Updating an object: use dot notation or square brackets. Use 'delete' keyword to delete.
        <li> Can use constructor notation to create many objects with sam properties.
        <li>'THIS' is used here! This.name this.rooms this.booked
        <li> This refers to one object and is commonly used inside functions and objects.
      </ul>

<h1> READING NOTES</h1>
  <h2>JAVASCRIPT & JQUERY // JON DUCKETT</h2>  
    <h3> Chapter 5: Document Object Model (pp 183-242)</h3>
      <ul>
      <li>The browser represents the page using a DOM element. 
      <li>DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.
      <li> You can select element nodes by their ID and CLASS attributes, by TAG NAME, or by using CSS selector syntax.
      <li> Whenever a DOM query can return more than one node, it will always return a NOdeList.
      <li>From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques.
      <li>An element node can contain multiple text nodes and child elements that are siblings of each other.
      <li>In older browsers, implementation of DOM is inconsistent (and is a popular reason for using JQuery).
      <li>Browsers offer tools for viewing the DOM tree.
      </ul>