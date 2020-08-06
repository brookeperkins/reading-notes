## URLSearchParams

(https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams)

<ul>
<li>URLSearchParams: for...of
<li>for (const [key, value] of mySearchParams) {}

<li>Constructor URLSearchParams() returns an object instance 
<li>URLSearchParams.append(), URLSearchParams.get()
<li>URLSearchParams: does not parse full URLs, removes the first ? from the string (if it exists)
</ul>

## URLSearchParams.toString() 

(https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams/toString)

<ul>
<li>URLSearchParams.toString() returns a query string used in URLs 
<li>Returns an empty string if there are no search params
<li>Example from site of URLSearchParams.toString() BELOW:
</ul>

    let url = new URL('https://example.com?foo=1&bar=2');
    let params = new URLSearchParams(url.search.slice(1));

    //Add a second foo parameter.
    params.append('foo', 4);
    console.log(params.toString());
    //Prints 'foo=1&bar=2&foo=4'

    // note: params can also be directly created
    let url = new URL('https://example.com?foo=1&bar=2');
    let params = url.searchParams;

    // or even simpler
    let params = new URLSearchParams('foo=1&bar=2');

## Location

(https://developer.mozilla.org/en-US/docs/Web/API/Location)

<ul>
<li>Location representations the URL/location of the object its linked to
<li>Properties: Location.ancestorOrigins, Location.href, Location.protocol, Location.host, Location.search, Etc
<li>Methods: Location.assign(), Location.reload()[reload current URL like a refresh], Location.replace(), Location.toString()[returns USVString with the whole URL]
</ul>

## Window: hashchange event

(https://developer.mozilla.org/en-US/docs/Web/API/Window/hashchange_event)

<ul>
<li>An event fired when the part of the URL starting and following the hashtag % changes
<li>Can be used in an addEventListener
</ul>

    //EXAMPLE FROM SITE
    function locationHashChanged() { 
    if (location.hash === '#cool-feature') { 
        console.log("You're visiting a cool feature!"); 
      } 
    } 

    window.onhashchange = locationHashChanged;