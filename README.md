# Tech-Blog

## Description
E-Post is a CMS-style blog where developers can publish their blog posts and comment on other developers’ posts as well.

## User Story
* AS A developer who writes about tech
* I WANT a CMS-style blog site
* SO THAT I can publish articles, blog posts, and my thoughts and opinions

## Acceptance Criteria
GIVEN a CMS-style blog site</br>
WHEN I visit the site for the first time</br>
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in</br>
WHEN I click on the homepage option</br>
THEN I am taken to the homepage</br>
WHEN I click on any other links in the navigation</br>
THEN I am prompted to either sign up or sign in</br>
WHEN I choose to sign up</br>
THEN I am prompted to create a username and password</br>
WHEN I click on the sign-up button</br>
THEN my user credentials are saved and I am logged into the site</br>
WHEN I revisit the site at a later time and choose to sign in</br>
THEN I am prompted to enter my username and password</br>
WHEN I am signed in to the site</br>
THEN I see navigation links for the homepage, the dashboard, and the option to log out</br>
WHEN I click on the homepage option in the navigation</br>
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created</br>
WHEN I click on an existing blog post</br>
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment</br>
WHEN I enter a comment and click on the submit button while signed in</br>
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created</br>
WHEN I click on the dashboard option in the navigation</br>
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post</br>
WHEN I click on the button to add a new blog post</br>
THEN I am prompted to enter both a title and contents for my blog post</br>
WHEN I click on the button to create a new blog post</br>
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post</br>
WHEN I click on one of my existing posts in the dashboard</br>
THEN I am able to delete or update my post and taken back to an updated dashboard</br>
WHEN I click on the logout option in the navigation</br>
THEN I am signed out of the site</br>
WHEN I am idle on the site for more than a set time</br>
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments</br>

## Languages
HTML, CSS, JavaScript, Node.js, Express.js, Express-Session, Npm Modules, dotenv Package, Sequelize, Connect-Session-Sequelize, MySQL2, Handlebars.

## Installation
The application require the use of Node.js, Express.js, Sequelize, MySQL2, Express-session &Connect-Session-Sequelize for running it.

## To Run the Application
Add a .env file to the root folder that contain the following:</br>
DB_NAME='tech_news_db'</br>
DB_USER='new_user'</br>
DB_PW='XXXXXX'</br>

## Screenshots
HomePage
![Screenshot of note adding](./public/images/home.png)</br>
Login and Signup page
![Screenshot of note viewing](./public/images/login-signup.png)</br>
Create Post
![Screenshot of note deleting](./public/images/create-post.png)</br>
Edit / Delete Post
![Screenshot of note deleting](./public/images/edit-delete-post.png)</br>
Add Comment / Upvote a Post
![Screenshot of note deleting](./public/images/addComment-upvote.png)</br>

## Github Page: 
https://github.com/amykep/Tech-Blog

## Deployed on Heroku at:
 https://salty-castle-67103.herokuapp.com