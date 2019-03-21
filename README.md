### Exotic Pet friend-finder
This full stack compatibility-based "FriendFinder" application takes in and compares user survey results then displays the name and picture of the best overall pet match.
 

Friend-finder uses Express to handle routing. It is deployed using Heroku so other users can fill it out.



    Server.js file requires the basic npm packages : express, body-parser and path. 
    The server.js file requires express and body-parser as npm packages, as well as node's internal path package.

    html_Routes.js file have two routes:
  
        A GET Route to /survey which displays the survey page.
        A USE Route as a default, catch-all route in a public folder that leads to home.html which displays the home page.

    api_Routes.js file has two routes:
        A GET route with the url /api/friends. This is used to display a JSON of all possible friends.
        A POST routes /api/friends. This is used to handle incoming survey results and used to handle the compatibility logic.

    Application's data is saved inside of app/data/friends.js as an array of objects. 
    
    
    
    
    The survey has 10 questions. Each answer is on a scale from 1 to 5 based on the user's level of agreement or disagreement with the question.  
    



### Links to view

* Deployed: https://exotic-friend-finder.herokuapp.com/
* Githubrepo: https://shannonruder.github.io/friend-finder/

* View a video walk-through: https://drive.google.com/file/d/14Zz_DDpHN_PS-MCqRIb0EyymorM12LZd/view





