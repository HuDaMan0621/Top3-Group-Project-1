# Project Name: top3

## Group Project By:

###### - Chris Harley
###### - Ying Hu
###### - Beau Dinh

**The purpose of 'top3' is to return the top 3 results of Restaurants, Hotels, Tours, Sightseeing, and Nightlife of the user input location.**

**Technologies used in this production includes: CSS, Javascript, HTML, Google maps API, and Triposo API.**

**Obstacles encountered during the production:
  *API: Triposo  
    1. Learned how to retrieve the information from the API
    2. Discovered ways to render information and images to the 'DOM' (Document Object Model) 
    3. Discovered the ALL keyword to retrieve information from the query
  *API: Google maps
    1. Researched google documentation to restrict the google maps API key for unauthorized access/use 
  *Functions: 
    1. Overcame obstacles on obtaining the information from the session storage and linked each field of information to the corresponding fields in the 'DOM' (Document Object Model)
  *UI:
    1. CSS Grid was implemented for the layout of the website

**Usage: Click on the link above to view the live website. [or Click Here](https://digitalcrafts-gp1-top3.netlify.app)

![Home Page](./dist/images/homepage.png)
**Home Page** - when the user inputs a location. 'top3' will search the API according to the user input and return the results on the next page. the submit button will change to "loading", the background will load a picture of the result; after 2 seconds, a new result page will load.

![Result Page](./dist/images/resultpage.png)
**Result page** - left 50% of the screen is the results and the other 50% of the screen is a google map.
The top portion of the result page will display a picture of the location, following by the name of the location, country, and score rating from the API. An about section can be read in the same section.

There will be 5 cards showing the top 3 of the results of the restaurants, hotels, tours, sightseeing, and nightlife. for example, the top 3 restaurants contain names of the restaurants and score ratings. Top 3 hotels contain names of the hotels and scores, so forth.

The map obtains the coordinates from the API and displays the location accordingly.

![Back To T0p](./dist/images/footer.png)
Lastly, we also included a footer on the bottom of 'top3' with an option to click to go back to the top. 

