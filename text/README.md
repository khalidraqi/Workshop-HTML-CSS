# Les bases xHTML
## Step 1 : Affichage d'une page xHTML
Écrire une page xHTML 1.1 qui affiche :
* un titre au niveau du bandeau de la fenêtre du navigateur
* le même titre dans le document
* un paragraphe
* Le document devra être valide conformément aux exigences du W3C
* Le document devra être écrit en UTF-8
* Le document devra contenir des caractères accentués
* Mettre un lien sur le validateur du W3C afin de permettre la validation par referer. Celle-ci cependant ne sera possible que si la page est placée sur un site web accessible depuis l'extérieur

## Step 2 : Affichage d'un texte avec tête, sections, navigation et pied de page en xHTML 5
Écrire une page HTML 5 qui affiche :
* un bloc d'entête header,
* un titre de premier niveau h1,
* un groupe d'entête hgroup,
* un bloc de navigation permettant d'accéder aux section définies ci-après.
* au moins deux sections génériques (section) pouvant correspondre aux chapitres d'un livre.
* un bloc de pied footer,

## Step 3 : Affichage des listes ordonnées et non ordonnées dans une page HTML 5
Reprenez ``Step`` 2 et ajoutez-y une liste composée (numéros et puces)

## STep 4 : Réalisation de tableaux xHTML
Réaliser le tableau ci-dessous :
* celui-ci doit être centré dans la page et occuper le 80% de la largeur de la fenêtre du navigateur
* largeur des bordures: 10 pixels (attribut CELLSPACING=); épaisseur de l'ombrage: 3 pixels (attribut BORDER=); détachement du texte par rapport aux bords: 5 pixels (attribut CELLPADDING=)
* la première colonne doit faire 80 pixels de large, les 2 autres se partageant le reste de la largeur
* dans les 2 premières lignes d'en-tête et dans la première colonne, le texte doit être en gras et souligné ; dans les autres cellules, il doit être en style normal et justifié à gauche
* réaliser alignement du texte "Xxxxx" au haut de la cellule, alignement du texte "Yyyyy" au bas de la cellule
* définir couleurs de fond
* placer une légende au bas du tableau
* les balises ``</TR>``, ``</TH>``, ``</TD>`` sont facultatives, mais il vaut mieux les mettre

## Step 5 : Affichage de grandeurs dans une page HTML 5
Écrire une page HTML 5 qui affiche :
* un titre (h1)),
* une grandeur de valeur 30 par rapport au min de 0 et au max de 100% (meter),
* une grandeur de valeur 3/4sans préciser de limites (meter),
* une grandeur de valeur médiane 50 par rapport au min de 0 et au max de 100 (meter) la valeur basse sera positionnée à 55 et la valeur haute sera positionnée à 90,
* une barre de progression de valeur 80% (progress),
* la date de ce jour (time),
* une zone de texte en surlignage (mark),
Faire en sorte que les navigateurs incompatibles affichent un valeur correcte.

## Step 6 : Test des ancres internes dans une page xHTML
Écrire une page xHTML 1.1 qui présente des liens sur des ancres internes à la page.
Faire en sorte que cette page soit suffisamment longue afin d'éviter que liens et ancres soient simultanément visibles.

## Step 7 : Page xHTML contenant des object
Écrire une page xHTML1.1 affichant contenant deux object de type text/HTML

## Step 8 : Page xHTML contenant des object pour visualiser des documents pdf
Écrire une page xHTML 1.1 affichant contenant un object contenant à son tour un document de type pdf

## Step 9 : Page HTML reproduisant un fichier audio
Écrire une page HTML 5.0 émettant le contenu sonore du fichier ici présent
Pour cela nous auron recours à la balise audio
Faire en sorte que :
* Les contrôles d'acvancement soien présents,
* La musique démarre automatiquement,
* Les contrôles d'acvancement soient présents,
* La musique tourne en boucle,
En cas de non support de la part du navigateur, présenter un lien permettant le chargement du fichier

## Step 10 : Page HTML affichant une video
Écrire une page xHTML 5 affichant la vidéo contenu dans le fichier ici présent
Pour cela nous aurons recours à la balise audio
Faire en sorte que :
* Les contrôles d'avancement soient présents,
* La video soit automatiquement chargée dès l'ouverture de la page,
* La vidéo tourne en boucle,
En cas de non support de la part du navigateur, présenter une applet chargeant le fichier flash ici présent
En cas de non support du flahs et de la balise video présenter un lien permettant le chargement du fichier vidéo.

## Step 11 : Page contenant un canvas
Écrire une page xHTML 5 :
* contenant un canvas dont la couleur de fond sera rouge
* afficher dans ce canvas un rectangle de couleur différende de celle du fond.
* donner au rectangle un contour blanc de 10 pixels de large.
Que se passe-il lorsque le rectangle est plus grand que le canvas ?

## Step 12 : Réalisation de formulaires HTML 5
Réaliser le formulaire ci-dessous :
* Pour mettre en page les différents éléments du formulaire (alignement des champs...), on utilise en général l'une des deux techniques suivantes :
    * définition de tous les champs dans bloc ``<PRE> ... </PRE>`` (où les ``<espace>``, ``<cr>``... sont significatifs)
    * définition de tous les champs dans un tableau (dont on peut rendre les bordures invisibles)
La seconde technique, utilisée ci-dessous, permet une mise en page plus sophistiquée
* Le texte en petits caractères italiques rouges est indicatif
* Test : si vous désirez voir la forme que prend la chaîne de caractère "URL-encodée" (contenant les variables du formulaire) que le script envoie au serveur lorsque l'on presse le bouton d'envoi, vous pouvez commencer votre formulaire par la balise ``<FORM METHOD="GET" ACTION="nom_de_votre_page.html">``