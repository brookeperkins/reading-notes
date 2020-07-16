<h1> READING NOTES</h1>
  <h2>The Past, Present, and Future of Local Storage for Web Applications</h2>
    <h3>https://diveinto.html5doctor.com/storage.html</h3>
    
<ul>
    <li>Native client application (appstore) vs web applications (apps accessible through browser).
    <li>Persistent local storage gives native client apps an edge over web apps. 
    <li>If the app needs more than key/value pairs, you can create your own database, file formats, etc. 
</ul>
<br>
<ul>
<li><strong>COOKIES</strong> used to store small amounts of data in persistent local storage. 
<li>Cookie downsides: included with every HTTP request and transmitting the same data over and over, making the web app slower. 
<li>Sends encrypted data when HTTP request (unless app is served over SSL)
<li>Cookie data is limited to approximately to 4kb. 
<li><strong>IDEAL SITUATION</strong> is: Lots of storage space, located on the client, data stays even with page refresh, and data is not transmitted to the server.
<li><strong>Local Storage Hacks Before HTML5</strong>: 
<li>IE, Microsoft DHTML Behaviors - userData
<li>2002 Adobe - Flash 6 (Local Shared Objects aka flash cookies)
<li>2006 Google Gears - open sourced browser plugin - after user permission, Gears can stored unlimited amounts of data per domain in SQL database tables. 
<li>HTML5: standardized API that natively and consistently works across multiple browsers without 3rd party plugins. 
<li>HTML5 uses localStorage - need to check for HTML storage first. 
<li>HTML5 storage can be used to save games progress. 
<li>Web SQL Database lets you do things like with backend database programming but with JavaScript. There are many types of SQL.