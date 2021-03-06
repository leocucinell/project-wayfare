# project-wayfare

## Description
Project wayfare is a city based blog where users can create blog articles about their travels. This app was made using Django and psql. 

[Check out the app!](https://bestwayfarer.herokuapp.com/)

## User Stories
### Sprint one
1. A user must be able to Login/sign up to the application from the home page. The navigation bar will host these buttons that when pressed, will display the modal to login/signup. 
2. After this, they will be redirected to their profile screen where they will see their name, current city, joined date, and list of posts.
3. A user must be able to update their profile information from the profile screen through use of a modal.
4. When a user clicks on a post, they will be redirected to a 'show'  page for that post; which displays the title, conten,t and author.
### Sprint two
1. A user will be able to view a 'cities' page at route "/cities/<int:pk>". This page will show the city name, a banner of the city, and a site wide header.
2. This city page will also contain a list of posts made about the city sorted from newest -> oldest. These posts will also be linked to their show pages.
3. Enable a ser to create a new post about the city, if authenticated. After this, be able to update or destroy the city if the user is the creator of the post.
### Sprint three
1. Make sure a user signing up for this app does not have the same username as anyone else in the app. 
2. All forms submited to the app will have to ass validation, they cannot be empty, posts cant be over 200 chars, comments cannot be over 200 chars.
### Sprint four
1. Create comment functionality. 
2. A user should be able to comment on a post, update their comments, delete their comments. 
3. Users must be authenticated to view any page besides the splash page.

# Wireframes
![The wireframes](./project_imgs/Wire.png)
# Photos
![The splash page](./project_imgs/Splash.png)
![The Profile page](./project_imgs/Profile.png)
![The Cities page](./project_imgs/Cities.png)
![The city post page](./project_imgs/City-post.png)
![The comments page](./project_imgs/Post-comment.png)
