hacking-angular-router
======================

	experiment in hacking angular router so all pages in multi page app are NOT destroyed
	ie 
	ng-view is not used
	
	instead ng-show is used on pre-existing dom pages (these could be loaded html partials)
	
	this could be useful for an
	animation where we slide from one page to another 
	as this would need both pages visible at same time
