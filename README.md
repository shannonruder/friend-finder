### friend-finder
This full stack compatibility-based "FriendFinder" application takes in and compares user survey results then displays the name and picture of the user with the best overall match.
 

Friend-finder uses Express to handle routing. It is deployed using Heroku so other users can fill it out.



    Used Express to handle routing. 

    Server.js file requires the basic npm packages : express, body-parser and path.

    HtmlRoutes.js file have two routes:
        A GET Route to /survey which displays the survey page.
        A default, catch-all route that leads to home.html which displays the home page.

    ApiRoutes.js file have two routes:
        A GET route with the url /api/friends. This is used to display a JSON of all possible friends.
        A POST routes /api/friends. This is used to handle incoming survey results and used to handle the compatibility logic.

    Application's data is saved inside of app/data/friends.js as an array of objects. 




### Links to view

* Deployed: https://exotic-friend-finder.herokuapp.com/
* Githubrepo: https://shannonruder.github.io/friend-finder/





