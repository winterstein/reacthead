
Modify the page <head> with React jsx tags in any component. Set title, metadata, etc.

WARNING: This does not work for Facebook or Twitter sharing metadata! 
Those tags must be added server-side - dynamic tags don't get picked up by the scrapers.
If you have a dynamic site, this can be a pain. One solution is to share a different url, where the server includes the og: meta tags

Example:

	<Title title='Hello World :)' />
