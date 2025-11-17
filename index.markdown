---
layout: single

---

Je suis Thomas Vercier, futur ingénieur spécialisé en traitement d’images et vision par ordinateur.
Passionné par la résolution de problématiques complexes, je recherche un premier poste technique pour approfondir mes compétences et en acquérir de nouvelles, que ce soit dans les technologies que je maîtrise déjà ou celles que je découvrirai.

J’ai un intérêt particulier pour le traitement d’images et la programmation bas niveau, notamment tout ce qui touche à l’optimisation de code et au calcul sur GPU.

En dehors du travail, je suis un grand passionné de chasse sous-marine, et qui sait, peut-être qu’un jour, ma passion pour la mer et les images se rejoindra dans un projet professionnel !

Je vous partage ici quelques images réalisées par moi-même sur [la Côte Bleue](https://fr.wikipedia.org/wiki/C%C3%B4te_Bleue).

<div class="ma-galerie-conteneur">

    <div class="colonne-gauche">
        
        <figure>
            <img src="/assets/images/vlcsnap-2025-11-17-14h30m14s750.png">
            <figcaption>Herbiers de posidonies</figcaption>
        </figure>

        <figure>
            <img src="/assets/images/vlcsnap-2025-11-17-14h37m31s316.png">
            <figcaption>Superbe sec</figcaption>
        </figure>

        <figure>
            <img src="/assets/images/vlcsnap-2025-11-17-14h42m55s700.png">
            <figcaption>Magnifique langouste</figcaption>
        </figure>

    </div>

    <div class="colonne-droite">

        <figure>
            <img src="/assets/images/vlcsnap-2025-11-13-11h53m47s901.png">
            <figcaption>2 sar commun dans leur pierre</figcaption>
        </figure>

    </div>

</div>

<style>
/* Conteneur principal qui crée les 2 colonnes */
.ma-galerie-conteneur {
    display: flex;
    flex-wrap: wrap; /* Permet de passer à la ligne sur mobile */
    gap: 15px; /* Espace entre les colonnes */
}

/* Colonne de gauche : prend 2/3 de la largeur */
.colonne-gauche {
    flex: 2; /* Prend 2 parts d'espace */
    min-width: 300px; /* Largeur mini avant de passer à la ligne */
    display: flex;
    flex-direction: column; /* Les images se superposent verticalement */
    gap: 15px; /* Espace entre les images de cette colonne */
}

/* Colonne de droite : prend 1/3 de la largeur */
.colonne-droite {
    flex: 1; /* Prend 1 part d'espace */
    min-width: 250px;
}

/* Style pour les images et descriptions */
.ma-galerie-conteneur figure {
    margin: 0; /* Enlève la marge par défaut */
}

.ma-galerie-conteneur img {
    width: 100%; /* L'image prend toute la largeur de sa colonne */
    height: auto; /* Garde les proportions */
    display: block; /* Évite les problèmes d'alignement */
    /*border-radius: 5px; /* Bords arrondis (optionnel) */
}

.ma-galerie-conteneur figcaption {
    font-size: 0.9em;
    font-style: italic;
    color: #555;
    text-align: center;
    margin-top: 5px;
}

/* Rendre le tout responsive sur mobile */
@media (max-width: 768px) {
    .ma-galerie-conteneur {
        /* Met les colonnes l'une en dessous de l'autre */
        flex-direction: column;
    }
}
</style>