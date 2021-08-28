Bonjour,

Entrons directement dans le vif du sujet, j'ai commencé l'exercice à 23h le 27/08/2021 et à l'heure ou j'écris ces lignes il est 7h17 et nous sommes le 28/08/2021. Je vais aller dormir j'écrirais le Readme dés mon réveil.


Rebonjour, alors techniquement la page se constitue comme demandé:

Premièrement j'ai créer mes pages index.html/css ainsi que mes dossiers "img" et "font" j'ai inclu dans mon fichier CSS ma font je ne savais pas si je n'avais le droit qu'à cette font du coups la page est entièrement réaliser en 'Karla-Regular'.

-Je me suis enuite attaqué au header qui contient 4 éléments "Nos clients", "Notre offre", "Le Studio", qui renvoient chacun à différents points d'ancrages 
(dans l'ordre Portfolio, slider, et à la loop infinite Texte) ainsi qu'un logo cliquable qui renvoi en haut de la page d'accueil. Le bouton contact lui ouvre une popup avec le formulaire mentionnant les cases obligatoires pour être soumis que je n'nai malheureusement pas eu le temps de relier à la Gender API car c'était la dernière section que j'ai faite dans le projet et j'étais déjà hors temps. La partie header m'a pris plus ou moins 1h.

-Ensuite, la bannière, j'ai perdu pas mal de temps sur cette section parce que je comptais partir sur un screenshot de base que je placerai en "Position: relative;" pour ne pas qu'il
chevauche le logo (qui est d'une sacrée longueure), c'est après que je me suis rendu compte qu'il fallait que le titre sois placé entre les balises <h1> donc j'ai changer de startégie et suis partis sur du texte en <h1> précédé par un paragraphe <p>. Cela étant dit je voulais encrer en background de la bannière un screen qui contenait le fond blanc de la section "Bannière" avec ce soulignement jaune tant convoité. Le tiens à préciser que l'encadrage des balises "<" et "/>" avec la balise <strong></strong> fut le seul moyen que j'ai trouvé pour les ajouté à mon titre. Le 
problème venait du fait de maintenir un alignement responsive avec le mot Shopify, je n'ai pas réussi et j'ai tout simplement (pour ne pas perdre plus de temps décidé de boycotté ce soulignement). 
Cette section avec la prise en compte du changement de stratégie m'a pris 1h30 plus ou moins.

-Vient ensuite le portfolio, alors ma stratégie de base pour gagner le plus de temps était d'intégrer un screenshot dans cette section et de définir une zone clickable au niveau du logo yoko, mais, car il y a un mais le problème du responsive m'a ramené à la réalité, et je suis retourner sur ce bon vieux "grid" system que j'ai fait à la main très rapidement, j'ai inclu toutes les photos des liens et ai fusionné l'image YOKO à un lien <a> pour qu'il soit cliquable. J'ai pu ensuite ajouter le lien "<voir plus/>" toujous entouré de balises <strong>" avec un a:hover jaune et underlined. Cette section était assez simple, la partie qui m'a pris le plus de temps était d'obtenir toutes les photos miniature depuis photoshop, de les renommer dans mes fichiers puis de les inclure dans ma grid. cette section à du me prendre 2h plus ou moins.

-Nous voici à ce fameux slider qui doit laisser entrevoir la prochaine image, j'ai utilisé la lib de Swiper que je ne connaissais que de nom et qui est très bien. Le slider défile en glissant la souris de gauche à droite ou inversemenent. J'ai trouvé ça sympa d'avoir une interaction autre que du clique sur la page. J'avais préparé l'image du texte nécessaire sur le slider qui aurait été en fixe sur cette section. Mais je ne réussissais pas à le faire apparaître par dessus les images du slider directement par manque de temps j'ai décidé d'omettre cette section et d'ajouter simplement le bouton "<voir plus/>"  dans une partie distincte en dessous du slider.
Cette partie m'a pris pas mal de temps en comptant les recherches d'une bonne lib de création de caroussel, la configuration pour créer l'effet de décallage des images et les tentatives d'intégration de l'image dans le slider. Le tout m'a pris plus ou moins 2h30.

-Le texte infinite à été assez simple je connaissais déjà la fonction pour la réaliser, il suffit de créer sa balise <marquee> de définir la direction dans laquelle il défile, le style de défilement ainsi que la vitesse à laquelle il défile. Le reste (design) se fait directement dans le fichier CSS en définissant une hauteur, une couleur de fond et d'écriture, etc. cette section à du me prendre une quinzaine de minutes. 
PS: J'ai passé un peu de temps à savoir quel texte affiché, j'ai failli vous afficher des citations drôles de présidents.

- Nous étions à 7h15 de travail, je me suis dis que j'allais pas m'arrêter en si bon chemin, et me suis lancé dans la création de la POPUP en me disant que ça n'allait me prendre que 5 minutes, j'ai donc créer une page HTML nommée Popup dans laquelle j'ai intégrer mes formulaires, que j'ai designé en css, ajouter les champs "required" et j'ai tenté de la relier à une gender API. Malheureusement, mon cerveau à ce niveau ne suivait plus vraiment j'ai passé près d'une heure dans mes recherches jusqu'à ce que j'arrive à un moment ou il fallait que je dorme. Je me suis donc arrêter là.

J'ai choisi intentionnellement de vous laisser le code tel qu'il était lorsque j'ai décidé de m'arrêter vous allez d'ailleurs voir du css dans le header. Au total j'ai passé près de 8 heures sur le test. Moi qui pensais le bouclé en 5h30 dans son intégralité.

Deux, trois choses que je souhaiterai savoir:
Comment vous vous y êtes pris avec ce maudit soulignement jaune ? 
Y'a t-il quelqu'un qui a déjà bouclé le projet à 100% dans les temps ? 
Est-ce vous qui avez créer cet exercice et si cela vient de vous est-ce une personne sortant de 42 qui l'a créer ?

Et pour finir une petite remarque : 
Cela faisait trèès longtemps que je n'avais pas eu de stimuli comme celui là, depuis l'école 42, j'ai (malgré tout) pris beaucoup de plaisir à la réalisation de cette exercice, j'ai dépasser le temps imparti et je n'ai pas terminer toutes les parties demandées. Mais je tiens à vous remercier pour ce challenge, et si, quelque soit votre choix vis à vis de cet exercice, vous avez d'autres exercices de ce type, je suis preneur ! 






