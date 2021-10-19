# EECS485-P3
Instagram Clone using HTML, React, Python, Flask, SQL.

React was used to allow for client-side dynamic pages on the home screen of instagram and also for individual posts.
Python and Flask were used for everything else including followers page, following page, explore page, user page, and login page. Flask cookies were used to store username and to authenticate users. Flask used to render templates created in HTML. Python used for REST APIs and SQL was used for database access and storage.

Screenshots from the project:

User Profile with ability to logout, upload new post, edit profile, view followers and following.
![This is an image](https://github.com/bquach2/EECS485-P3/blob/main/Screen%20Shot%202021-10-19%20at%206.17.09%20PM.png)

Screenshots from home page:

Each post has the ability to like/unlike either by pressing the like button or by double clicking the image by making a call to REST API, which inserts a new like into the SQL database. Now we use React to update state, updating the view.

Before liking
![This is an image](https://github.com/bquach2/EECS485-P3/blob/main/Screen%20Shot%202021-10-19%20at%206.19.53%20PM.png)
After liking
![This is an image](https://github.com/bquach2/EECS485-P3/blob/main/Screen%20Shot%202021-10-19%20at%206.19.57%20PM.png)


Also have client-side updating comments by being able to delete and create new comments without reloading the page. Similar to liking a post, make a REST API call to create a new or delete a comment. Update is made to state, rendering new data on the screen.

![This is an image](https://github.com/bquach2/EECS485-P3/blob/main/Screen%20Shot%202021-10-19%20at%206.20.17%20PM.png)
![This is an image](https://github.com/bquach2/EECS485-P3/blob/main/Screen%20Shot%202021-10-19%20at%206.20.12%20PM.png)
![This is an image](https://github.com/bquach2/EECS485-P3/blob/main/Screen%20Shot%202021-10-19%20at%206.20.21%20PM.png)
