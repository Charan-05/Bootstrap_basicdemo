# Bootstrap_basicdemo
meta charset="utf-8"
States the character set that is used to write the website. In this case, UTF-8 refers to Unicode.
meta http-equiv="X-UA-Compatible"
Determines the version of Internet Explorer that should render the page. Using Edge mode, it’s set to use the highest mode available.
meta name="viewport"
Ensures that the page has a 1:1 ratio with the viewport size.
link href="css/bootstrap.min.css" rel="stylesheet"
This is where we add the Bootstrap core CSS.
src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"
Loads jQuery via Google CDN. It’s better to load it from the CDN via HTTP as the files can be cached for a year.
src="js/bootstrap.min.js
Adds the Bootstrap core JavaScript. This syntax must be below the jQuery syntax to function properly. The addition process can be done via Google’s URL or a manual download.
