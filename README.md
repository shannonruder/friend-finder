### exotic pet friend-finder
This full stack compatibility-based "FriendFinder" application takes in and compares user survey results then displays the name and picture of the user with the best overall match.
 

Friend-finder uses Express to handle routing. It is deployed using Heroku so other users can fill it out.


    
    Used Express to handle routing. 

    Server.js file requires the basic npm packages : express, body-parser and path.

    HtmlRoutes.js file have two routes:
        A GET Route to /survey which displays the survey page.
        A default, catch-all route in a public folder that leads to home.html which displays the home page.

    api_Routes.js file has two routes:
        A GET route with the url /api/friends. This is used to display a JSON of all possible friends.
        A POST routes /api/friends. This is used to handle incoming survey results and used to handle the compatibility logic.

    Application's data is saved inside of app/data/friends.js as an array of objects. 
    
    
    
    
    The survey has 10 questions. Each answer is on a scale from 1 to 5 based on the user's level of agreement or disagreement with the question. The server.js file requires express and body-parser as npm packages, as well as node's internal path package. html_routes.js contains a GET route for displaying the survey, as well as a default USE route for the home page. api_routes.js contains a GET route to display all possible matches as well as a POST route to handle incoming survey results and perform the compatibility logic.
    



### Links to view

* Deployed: https://exotic-friend-finder.herokuapp.com/
* Githubrepo: https://shannonruder.github.io/friend-finder/





