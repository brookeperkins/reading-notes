## How I explained REST to my brother

https://gist.github.com/brookr/5977550

<ul>
<li>Roy Fielding: helped write first web servers that sent documents across the Internet, researched why the web works the way it does, helped write "HTTP" protocol
<li>HTTP: tells the browser what protocol to use, is capable of describing the location of something anywhere in the world from anywhere in the world! (GPS coordinates)
<li>REST: architectural style on which the whole web is built. REST provides a definition of a "resource" (a concept which HTTP points to)
<li>web pages are representations of resources
<li>browser asks for the web page representation of a resource/concept
<li>machines used to communicate A to B, but now machine A needs to be able to tell machine B about a resource that's on machine C (and more)
<li>redirect
<li>polymorphism applies to REST by saying that we can have multiple nouns, ie things to be selected that have the same verb applied to them I.E. POST GET PUT DELETE. Which relate to SQL with INSERT, SELECT, UPDATE, DELETE