##PLOTS LEAFLET VIEWER##

This is a leaflet-based tsomething msomething ssomething (TMS) viewer which accepts a TMS URL as a GET parameter. Good for fullscreen map viewing and embedding.

Serve the repository directory as static pages on a webserver.

The index.html page accests query parameters for a TMS as well as others, following this syntax:

* tms - with trailing slahs, such as http://mapknitter.org/tms/lone-rock-pond/
* lon - center longitude, required
* lat - center latitude, required
* zoom - zoom level, default 18
* minZoom - minimum zoom level, default 15
* maxZoom - maximum zoom level, default 22

Use it to make embed codes:

    <iframe style="border:none;" width="500" height="375" src="http://archive.publiclaboratory.org/leaflet/?tms=http://mapknitter.org/tms/lone-rock-pond/&amp;lon=-73.0733&amp;lat=43.96055&amp;zoom=18"></iframe>

