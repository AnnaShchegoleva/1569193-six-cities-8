# Personal project «Six cities»

"Six Cities" is a service for travelers who do not want to overpay for rent. Choose from six popular travel cities and get a up-to-date list of rental deals. Detailed information about housing, showing the object on the map, as well as a laconic service interface will help you quickly choose the optimal offer.


---

### Application Pages

The application consists of several pages: Main (/), Sign In (/login), Favorites (/favorites) (private), Room (/offer/: id).

The Favorites page is available only to authorized users.

If the user is authorized, the Sign In page redirects to the Home page.

If the user is not authorized, then when trying to go to the private page, a redirect to the "Sign In" page (/login) is performed.

The header of each page displays a link to the Sign In page (if the user is not authorized) or the user's email and the Sign Out button (if the user is authorized).

Clicking on the "Sign Out" button leads to the end of the session - leaving the closed part of the application.

Clicking on the user's email in the header takes you to the Favorites page (/favorites).

Accessing a non-existent page (for example, through the address bar) does not lead to errors in the application, but is correctly processed by routing. The user is redirected to the 404 page. The design of the page remains at the discretion of the student. In the simplest case, it can be a page with the text 404 Not Found and a link to go to the main page of the application.

---

*Main page*

The main page displays a list of cities for which it is possible to request rental offers: Paris, Cologne, Brussels, Amsterdam, Hamburg, Dusseldorf.

The server always returns information only for these six cities.

After downloading the application, the first city from the list on the main page - Paris is always active. Rental offers are loaded for this city.

On the map, sentences are displayed as blue markers.

When you change cities, the quotation list and map are updated.

The quotation list header displays the number of quotations available. 

The Favorites button of each sentence. Clicking on the "Favorites" button adds a card to your favorites. Clicking on the "Favorites" button again performs the opposite action - removes it from favorites. If the user is not authorized, the user is redirected to the Sign In page. The icon on the button changes depending on the action: add to favorites (transparent), remove from favorites (blue).




