## Ce que tu vas faire

Tu vas créer un jeu de société auquel tu pourras jouer avec tes ami·e·s pour t'amuser !

Tu peux baser ton jeu de société sur un jeu auquel tu as déjà joué.

Ton jeu de société devra respecter la **fiche de projet**.

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Une <span style="color: #0faeb0">fiche de projet</span> décrit ce qu'un projet doit faire. C'est un peu comme se voir confier une mission à accomplir.
</p>

Tu devras décider du type de jeu que tu veux faire et à qui il est destiné.

Ton jeu devrait :

- Afficher une image que tu as conçue sur les LED
- Laisser un·e joueur·euse démarrer le jeu
- Jouer des sons et/ou afficher des icônes sur les LED
- Laisser les joueur·euse·s contrôler le jeu en utilisant des boutons, le logo tactile, le mouvement ou les sons
- Afficher un résultat gagnant ou un prix à la fin du jeu

Ton jeu **pourrait** :

- Laisser l'utilisateur·trice entrer le nombre de joueur·euse·s
- Utiliser un minuteur
- Avoir des niveaux
- Garder la trace d'une valeur ou d'un score élevé
- Avoir une fonction de réinitialisation
- Enregistrer des données
- Organiser le code en fonctions
- Être alimenté à partir du boîtier de piles

### Trouver des idées

Pense à la façon dont ta partie va commencer, comment un·e joueur·euse gagnera la partie, et comment le jeu se termine au fur et à mesure que tu étudies ces exemples de projets pour obtenir plus d'idées :

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1">  

### Chaises musicales

Dans ce projet, le micro:bit est utilisé pour contrôler un jeu de chaises musicales.

Le nombre de joueur·ses est fixé à `4`, alors aligne `3` chaises pour jouer au jeu !

- Regarde l'animation de démarrage de quelqu'un assis sur une chaise.
- Une flèche clignotante pointe vers le logo tactile.
- Lorsque tu touches le logo :
  - On te montre un compte à rebours 3, 2, 1, puis une image d'une chaise vide.
  - Une mélodie est jouée pendant une durée aléatoire (entre 3 et 15 secondes).
  - Tous les joueur·ses doivent se déplacer autour des chaises pendant que la musique joue !
  - Lorsque la musique s'arrête, une animation « assis » s'affiche.
  - Tous les joueur·ses doivent essayer de s’asseoir sur une chaise. Le joueur ou la joueuse resté·e debout est retiré·e du jeu.
  - S'il reste plus d'un·e joueur·se dans la partie, `-1` s'affiche pour t'indiquer de retirer une chaise et une flèche clignotante pointe à nouveau vers le logo tactile.
  - Lorsqu'il ne reste qu'une seule chaise, la personne qui s'assoit dessus gagne (et une icône de visage souriant s'affiche).

Tu peux définir le nombre de joueur·ses à l'aide des boutons A et B.

Tu peux secouer le micro:bit pour réinitialiser le jeu à `4` joueur·ses.

</div>

<div>

[👀 Voir le code 👀](https://makecode.microbit.org/_8o7R5MEfC4m3){:target="_blank"}

<div style="position:relative;height:0;padding-bottom:125%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_8o7R5MEfC4m3" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

</div>

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1">  

### Retournement de bouteille

Dans ce projet, le micro:bit est utilisé pour afficher le score dans un jeu de retournement de bouteille.

N'importe quel nombre de joueur·euse·s peut jouer au jeu, mais assure-toi de jouer avec plus d'une personne !

- Suis les instructions de démarrage à l’écran.
- Lorsque tu appuies sur le bouton A :
  - Des instructions supplémentaires et le numéro du joueur ou de la joueuse actuel·le sont affichés.
  - Tu peux commencer à retourner la bouteille, chaque atterrissage de la bouteille te donnera un point au score.
  - Tu peux appuyer sur le bouton B pour terminer le tour du joueur ou de la joueuse et voir le score.
  - Appuie sur le bouton A pour que le joueur ou la joueuse suivant·e retourne la bouteille.

Tu peux appuyer sur le bouton logo pour réinitialiser le jeu et recommencer.

</div>

<div>

[👀 Voir le code 👀](https://makecode.microbit.org/S88052-89971-86401-86445){:target="_blank"}

<div style="position:relative;height:0;padding-bottom:125%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=S88052-89971-86401-86445" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

</div>

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1">  

### Bop-it !

Dans ce projet, le micro:bit est utilisé pour reproduire le périphérique Bop-it. Les joueur·euse·s doivent :

- Regarder l'animation de démarrage pour comprendre les différentes tâches que tu dois accomplir.

1. **Lève-le** — lève le micro:bit au-dessus de ta tête
2. **Crie** — crie au micro:bit
3. **Secoue-le** — secoue le micro:bit
4. **Bop it** — appuie sur les boutons A et B

- Appuie sur le logo pour démarrer le jeu.
- Complète les tâches avant que ton temps ne s'écoule.
- Tu bénéficieras de temps supplémentaire après avoir terminé chaque action.
- Lorsque le temps est écoulé, ton score s'affiche sur les LED.

</div>

<div>

[👀 Voir le code 👀](https://makecode.microbit.org/S80414-03592-06914-91553){:target="_blank"}

<div style="position:relative;height:0;padding-bottom:125%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=S80414-03592-06914-91553" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

</div>
