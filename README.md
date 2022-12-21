OpenClassrooms # Projet-2---Intégration-site-agence-de-voyage

/* Project overview */
Welcome to Booki, a (fictional) travel booking website. I developed this webpage based on a Figma design (see below) using HTML and CSS only. It is currently a pure front-end project / interface project with no JavaScript.
My website is fully responsive. It has been tested down to 300px wide. It has been sucessfully tested on Chromium and Firefox on desktop, and Safari on mobile.

/* Technical brief and specs */
- navigation bar with hover effect
- input field for searching cities
- filter buttons with hover effect
- clickable accomodation and activity cards
- fully responsive for desktop, tablet and mobile displays with breakpoints for tablet (992px) and mobile (768px) and a maximum width of 1400px

/* Live website */
https://jade-pudding-a6fc50.netlify.app/

/* Figma design*/
https://www.figma.com/file/aen32jonHhD7JnIEL2b3sE/Maquettes-Booki-(desktop%2C-mobile%2C-tablette)?node-id=3%3A0&t=ZTWgrw8YVzgPl3HJ-0

/* Validators */
HTML: https://validator.w3.org/ PASSED (1 warning)
CSS: https://jigsaw.w3.org/css-validator/ PASSED (1 error thrown by by fontawesome.css - not my code)

/* Changelog */

v1.1
- changed section bg color;
- set mailto for Nous Contacter;
- changed icon color to blue;
- fixed buttons horizontal centeringinto magnifying glass icon;
- imported FA through CSS rather than script;
- renamed folders with lowercase;
- imported normalize.css;
- used <article> tagon cards;
- separated css into 3 CSS files: 1 for desktop, 1 for mobile, 1 for tablet ;
- created classes for nav/form etc. selectors;
- changed grid to flex for accomodation section;
- reworked cards HTML structure (changed the <a> wrapping> and used h3) and used absolute positionning for anchors;
- for .card: wrapped  h2 p and stars in a div;
- used h1 tag;
- checked breakpoints; 992px for desktop / 768px for mobile;

v1.2
-  fixed display above 992px;
-  fixed extra CSS folder on github and check indentation;
-  merged .container with the parent tag;
-  used h4 for "plus de 500 logements...";
-  created classes for "naked" selectors h1 etc. / rework selectors that use a semantic tag (eg div.info => .info;
-  renamed @media screen and (min-width: 769px) and (max-width: 992px) {;
-  min-width 320 => tested down to 300px;
-  image width issue on FF 


prepare a powerpoint

during presentation:

pass the tests
show different browsers
show github and commits
search reasons why I get errors on validators


potential questions:
why is important to go through validators
what's the most difficult part of the project?
what's semantic
pkoi petites images (thumbnail)

