OpenClassrooms # Projet-2---Intégration-site-agence-de-voyage
 
 /* Maquette Figma */
https://www.figma.com/file/aen32jonHhD7JnIEL2b3sE/Maquettes-Booki-(desktop%2C-mobile%2C-tablette)?node-id=3%3A0&t=ZTWgrw8YVzgPl3HJ-0

/* Sessions mentorat */
-13/12/22
Questions: 
1) solution propre pour l'icone FA info ? le padding ne donne pas un résultat parfaitement centré.
Padding ajusté. => explaiin during oral how I had to hack it,
Aligner l'icone par rapport au texte? => center vertically with text

2) Code pour section hebergement ok ? problèmes pour le positionnement de l'image et la gestion des width et height


feedback:
[x]changer gris des sections
[x]pkoi petites images (thumbnail)
[x]mettre un mailto pour Nous Contacter
[x]mettre le max-width 1400 sur le body
[x]couleur des icones en bleu
[x]NE PAS centrer les icones dans les boutons de filtre -> ajuster la taille du bouton au contenu. fit-content?
[x]mobile: changer le mot RECHERCHER en icone loupe
[x]importer FA avec CSS et non en script
[x]nommer dossiers en minuscules
[x]normalize.css?
[x]use <article> tag; be able to explain semantic HTML for oral
[x]use 3 CSS files: 1 for desktop, 1 for mobile, 1 for tablet 
[x]create classes for nav/form etc. selectors
[x]change grid to flex
[x]indent cards correctly <a> <div>
[x]for .card: wrap h2 p and stars in a div
[x]use h1 tag
[x]check breakpoints; 992px for desktop / 768px for mobile

-19/12/22

Questions :
 - si j'utilise github desktop, est-ce que j'ai besoin de passer par de la ligne de commande ou d'utiliser shellbash pour le versionnage avec Git?

 - en utilisant l'outil de vérification du CSS, il y a une erreur sur le fichier normalize.css et sur les fichiers font-awesome. Comment faire ?

 feedback:
[x] fix display above 992px
[] fix extra CSS folder on github and check indentation
[] merge .container with the parent tag
[] use h6 for "plus de 500 logements..."
[] search reasons why I get errors on validators
[] create classes for "naked" selectors h1 etc. / rework selectors that use a semantic tag (eg div.info => .info
[] rework @media screen and (min-width: 769px) and (max-width: 992px) {
[x] min-width 320

prepare a powerpoint

during presentation:
pass the tests
show different browsers
show github and commits

potential questions:
why is important to go through validators
what's the most difficult part of the project?
what's semantic


