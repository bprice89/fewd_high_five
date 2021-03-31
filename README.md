# fewd_high_five
CLIFF NOTES
-Webpage is built with a mobile first approach and is fully responsive.
 
GITHUB COMMITS
-10+
 
Media Queries
-3 different pixel sizes used on the NAVBAR to hide links and buttons and turns them into a hamburger button. First query hides links, second query hides buttons and links.
-Media queries used to change the main content on the homepage from an auto template grid to a 1fr 1fr grid layout.
-Media queries used on the service page to change the main content from flexbox columns to flexbox rows.
 
CSS FEATURES
-Hamburger button built on NAVBAR.
-CSS Flexwrap used on NAVBAR.
-Flexbox used on the services page to align content from columns to rows.
-CSS Grid used on the main content of the homepage to switch from columns to 1fr 1fr that split the screen in half.
-Hover animations used on buttons.
-:nth-child used to adjust the picture sizes on the services page when shown on different screen sizes. 
-Form built and able to show and hide using a checkbox feature.
 
JAVASCRIPT
-I used a javascript function along with jquery to activate my hamburger button. The function uses the “click” sound to toggle the button from active to inactive and the script is written on the HTML page. This should fit the javascript requirement of *Show/hide one or more content areas or elements on your site through clicking a button or some other interaction-must be done with some Javascript code.* 
 
 
FULL DESCRIPTION
-Hello and welcome to my project. My website is based on my brother's installation company and gives some services that he handles. The project is located under index.html and has been tested and works on different browsers such as Chrome and Edge; the page is fully responsive and built mobile first.
 
NAVBAR
-On the home page in desktop mode you will see a Navbar at the top that  uses the CSS property flex wrap and has multiple links to different pages(not all pages available yet). If you hover over the login and sign up buttons you will notice a CSS hover animation that turns the buttons different colors. I used media queries to adjust the NAVBAR to different screen sizes. At a pixel width of under 1000px(tablet mode) you will see the NAVBAR buttons change to a hamburger button built with CSS that hides the other page links but leaves the login and signup buttons visible. You can click the hamburger button to show the other links. This feature uses JAVASCRIPT with a click sound/toggle feature to make it active and non-active. If you adjust the screen to under 600px(mobile mode) the login and signup buttons hide in the hamburger button as well.
 
MAIN SECTION HOME PAGE
-The home page is built on CSS GRID and the template is in auto, once the screen reaches a pixel size of 600px I used a media query to switch the grid to a fractional unit of 1fr 1fr, this splits the screen into 2 halves and shows the logo and name of the company along with a get started button. If you click the get started button it pulls up a login/signup form that you can enter your name and password. This form uses a checkbox show hide feature to display the form. This button also has a css hover animation.
 
SERVICES PAGE
-The services page uses the same NAVBAR as the home page. The main content on the services page lists all the services the company can perform and uses flexbox property and switches from flex-direction column in mobile mode to flex direction row. I also used th nth-child CSS feature to adjust the sizes of the pictures under different screen sizes.
