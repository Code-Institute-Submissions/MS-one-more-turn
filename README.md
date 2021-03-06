# Milestone Project One:

1. Purpose of the project:
________________________________________

The purpose of this project is to provide a game review website that serves to inform the user of Andrew’s reviews, and invite them to collaborate/request future reviews.
The idea for this website is based on a blog that I started regarding computer games, using Weebly. I didn’t have any web development skills when I created the blog,
and once I learned HTML and CSS, updating and upgrading my blog into a real website was the first thing that occurred to me. It started life as “grababrew” then was 
changed to “One more Turn” which I felt more adequately represents the feeling you have when a game is really good, and you don’t want to stop playing. 

2. User Goals/stories:
________________________________________
a.	As a Potential Employer for a Coding Role, I want to view Andrew’s website, to see how he performs as a Full stack developer. 
I want to be able to navigate the website and compare it to others, of similar scope.

b.	As a Potential Game buyer, I want to understand Andrew’s perspective on games I may be interested in, in the form of reading his reviews. 

c.	As a Potential Collaborator, I want to be able to contact Andrew directly through the site and have easy access to his reviews and social media presence. 
I want to be able to submit a game review request.

Stakeholder Goals:
________________________________________
To lead the user to read Andrew’s reviews and contact/connect with Andrew on social media/through a contact form if user is a potential collaborator or client.

3. Typography and colour scheme:
________________________________________
a.	Font - Exo and Sans serif. This is because they worked well in the Code Institute models (i.e. easy to read) 

b.	Icons - taken from Font Awesome, mainly in order to comply with existing conventions, e.g. a house or similar to represent the Homepage.

c.	Colours – muted use of colours throughout, in order to draw visual attention to the review sections of the website. Red, white and black are the primary colours.

d.	Images – photos and screenshots taken of games and game accessories (e.g. dice) to be used as icons for the relevant games, and background images 
for the relevant sections of the website.

4. Features:
________________________________________
a.	Header to consist of the website name, along with links to the Home Page, Video games review section, Tabletop games review section, 
About webpage and a contact page (essential!). In the future, this may be expanded to include Playthroughs, forum, gallery and podcast sections.(non-essential)


b. 	Footer to consist of social media links and the website name again (essential) and in the future this could be expanded to include a Patreon link, 
and an additional call to sign up (non-essential).

c. Homepage. The intent of the homepage is to provide a visually appealing but clean, minimalist introduction to the website, with a concise description 
of the website and 2 images that link to the review sections of the website.

d. Review sections- There are 2 review sections, one for digital (video, computer, console) games, and the others for tabletop (card,boardgames) games.  
These will have a selection of game reviews, and the layout will be rows. When clicked upon, user is taken to a dedicated page for that review.

e. About. This is a simple page that outlines the philosphy of the website.

f. Contact. This page will be a simple contact/request for review form, with all fields obligatory.

g. placeholder review - this is linked to reviews that are not yet complete, as it will take time to create proper reviews.

f. thankyou page. This page exists to thankl users who fill out the contact form.

The minimal viable product for this website is a (header) b (footer) c (homepage) d (review paqges) and e (contact page.)

5. Wireframes:
________________________________________

The wireframes can be accessed from the "wireframes" folder, and also directly here:

https://github.com/ANDREWAHN-UK/MS-ONE/blob/master/wireframes/MS1%20mobile.bmpr

https://github.com/ANDREWAHN-UK/MS-ONE/blob/master/wireframes/MS1%20mobile.pdf

https://github.com/ANDREWAHN-UK/MS-ONE/blob/master/wireframes/MS1.bmpr

https://github.com/ANDREWAHN-UK/MS-ONE/blob/master/wireframes/MS1.pdf

6. Technology:
________________________________________
The website was created using Bootstrap, html5 and css3. No javascript was used, except what is bundled with Bootstrap. I originally built this website without any bootstrap,
as I felt intimidated by the Boostrap learning curve. However, I could not get the viewports to work consistently when testing it, so I rebuilt the website using Boostrap.
The main utility of Bootsrap in this website was in providing a header that collapses on smaller viewports, and also built in sclaing for various viewports.

When I started the website, Github and Gitpod were experiencing some issues, so I did the initial coding in visual studio code. I then miograted this to Gitpod and Github.

7. Testing:
________________________________________

I used Opera and Chrome, and tested it using the dev tools there, accessed in chrome by right click + inspect + toggle device toolbar + select various devices. 
In Opera right click + inspect + toggle device toolbar +  select various devices. 

Screenshots showing the testing are available from the "screenshots for testing" folder:

https://github.com/ANDREWAHN-UK/MS-ONE/blob/master/screenshots-for-testing

I used https://validator.w3.org to validate the html and https://jigsaw.w3.org/css-validator/ to validate the CSS.
There were some minor errors (like lone div tags) in the HTMl but the CSS threw up very many errors, ALL of them related to Bootstrap, saying things like "ms flex box not recognised."

I did not encounter many bugs the second time around, although I did have some issues positioning the text form for the contact webpage. I solved that by initially setting all 
margins to auto, and using "justify content center," "align items center (when needed,)" and then adjusting the margins and padding to get the desired appearance.

I also had some issues with gaps appearing between images, with white space showing, which was not wanted. 
I solved this by using "no gutters" when constructing the rows and columns.

Lastly, the images in the review pages were not displaying correctly on Tablets, namely the Kindle HDX and Ipad, but not the Ipad Pro.
Experimenting revealed that "col-md-6" was causing images to take up only half the row, so removing it fixed this issue.

8. Deployment:
________________________________________

I used Github pages and Netlify to deploy the website. Github is the preferred website for the Coding institute, and I chose Netlify because it connects very easily to Github, 
and is thus a very suitable backup.

Github: https://andrewahn-uk.github.io/MS-ONE/index.html

Netlify: https://mystifying-poitras-75f386.netlify.app

I have noticed that Github occasionally doesn't update properly, but in my limited experience Netlify has yet to fail.

9. Credits:
________________________________________

In making this website, I made extensive use of google search, both for help concpetualising how the code would look and work, and for actual assets, such as images.
I also used the below resources:


Bootstrap CDN: https://getbootstrap.com/docs/4.0/getting-started/introduction/

https://www.w3schools.com

https://wyrmwoodgaming.com/products/rtd-naughty-dice/

https://aow.triumph.net/gallery/

steam.com

https://unsplash.com for several photos

www.shopify.com/

codeinstitute.net

stackoverflow.net

google.com

youtube.com

boardgamegeek.com

kickstarter.com

https://mongolcult.com

https://www.quartertothree.com/fp/

