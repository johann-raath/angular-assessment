# Warp Angular Assessment

Create a UI that lists all of the countries in the world using: https://gitlab.com/restcountries/restcountries.

The UI must lazy load the main modules of the project. 

The design and layout of the project is up to the developer.
	
	
The UI must:

Display the countries as a grid, using their flag as the picture with their coat of arms as an icon over their flag.

Have filters to filter countries by region.

Have a search to search country by common name or FIFA code.

Have a way to select multiple countries then add them to a favourites list.	

Favourites must be saved in local storage, using a service that acts as your post endpoint, so that they are not lost when reloading the page.

The user must be able to click on a country flag that brings up a modal that:
Contains basic information about the country such as:

*test

1.Common Name.
2.Region.
*Fifa code.
*Population (formatted with thousand separators) 
*Languages.
*Country local time and time zone.
*Capital city.
*A list of their currencies.
*A link to view on map (either Google or OpenSteertMaps)
Have favourite/Unfavourite.
Have a close button.

Have a way to access your favourites page.
The favourites page must:
Have a list of all my favourite countries.
Have a way to unfavourite a country.
Have a way to view the detail of a country when I click on it using a sub route.
The details page must:
Have all the same details as the modal on the listing page.
A form that:
allows the user to make a comment about the country
allows the user to optionally add a picture to a comment using a Google images URL.
automatically sets the time stamp on each comment formatted as: Thurs, 01 April 2023 10:36AM					

Supply the user with a notification when things happen.	





Criteria

	The developer will be critiqued on:
		
Their ability to understand and use the API.
Implementation of typed requests and responses.
Re-usability of their components and code.
House keeping of their project. Modules, components and styling.
Use of local storage to persist state.
Use of services and observables.

Git
		
	Final assessment can be pushed to the repo supplied in the email using the supplied 	credentials.
