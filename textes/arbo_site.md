# arborescence du site "Cartographie des structures de la médiation numérique en Bourgogne-Franche-Comté"

## équipe 

- Jean-Christophe (typologies, design, jeux de données, data, contenus)
- Bruno Louis (design, contenus, technique)
- Corine (contenus)

## arborescence (tous les liens sortants s'ouvrent dans une nouvelle fenêtre)

```
.
+-- Logo MedNum BFC [https://www.mednum-bfc.fr/]
+-- La cartographie des lieux de médiation numérique en BFC
+-- La cartographie [home]
|   +-- La carte: vue carte par défaut - niveau de zoom Bourgogne-Franche-Comté
|   +-- La MedNum BFC [https://www.mednum-bfc.fr/]
|   +-- Les données [https://bfc-carto.netlify.app/les-donnees]
|   +-- Aide [https://bfc-carto.netlify.app/aide]
|   +-- Mentions légales [https://bfc-carto.netlify.app/mentions-legales]
+-- Nos offres et services [https://www.mednum-bfc.fr/nos-offres-et-services/]
+-- A propos [https://www.mednum-bfc.fr/mednum-bfc-la-mission-regionale-pour-la-mediation-numerique/]
+-- Blog [https://www.mednum-bfc.fr/le-blog/]
+-- Nous contacter [https://www.mednum-bfc.fr/pour-nous-contacter-cest-simple/]
```

## footer
```

+-- footer (trois colonnes)
|   +-- MedNum BFC (renvoyer vers leurs sites)
|   |   +-- Accueil [https://www.mednum-bfc.fr/]
|   |   +-- Contact [https://www.mednum-bfc.fr/pour-nous-contacter-cest-simple/]
|   |   +-- À propos [https://www.mednum-bfc.fr/mednum-bfc-la-mission-regionale-pour-la-mediation-numerique/
|   |   +-- Nos offres et services [https://www.mednum-bfc.fr/nos-offres-et-services/]
|   |   +-- Mentions légales
|   +-- Nos sites
|   |   +-- Le réseau régional des acteurs du numérique [https://humhub.bfc.link/]
|   |   +-- Numérique & Territoires [https://www.numerique-bfc.fr/]
|   |   +-- Cartographie des structures de la médiation numérique en Bourgogne-Franche-Comté [https://bfc-carto.netlify.com/]
|   +-- Nos partenaires
|   |   +-- GIP Territoires Numériques BFC [http://www.ternum-bfc.fr/]
|   |   +-- Conseil régional de Bourgogne-Franche-Comté [https://www.bourgognefranchecomte.fr/]
|   |   +-- Banque des Territoires [https://www.banquedesterritoires.fr/]
|   |   +-- Mission Société Numérique [https://societenumerique.gouv.fr/]
|   |   +-- La MedNum [https://lamednum.coop/]

+-- Par défaut, "propulsé par ApiViz etc" 

```

## design

- Logo principal (dans la barre de navigation): MedNum BFC 
- Sélection des modes de vision des données: à minima carte, liste, tableur
- Quelles couleurs ? Les trois couleurs principales utilisées sur le site de MedNum BFC sont : 
  - #293e86 (bleu foncé), 
  - #f24c61 (rouge) et 
  - #37bec1 (turquoise).
- Quelles typos? La typo utilisée sur le site de MedNum BFC est Poppins https://fonts.google.com/specimen/Poppins
- Quelle URL ? https://cartographie.mednum-bfc.fr/
- Quel nom pour cette carte ? Cartographie des structures de la médiation numérique en Bourgogne-Franche-Comté
- site uniquement en français, pas de version multilingue

## filtres 

Note: on doit pouvoir cocher plusieurs catégories dans chaque filtre et plusieurs filtres ensemble.
```

+-- Département
|   +-- Côte-d'Or
|   +-- Doubs
|   +-- Haute-Saône
|   +-- Jura
|   +-- Nièvre
|   +-- Saône-et-Loire
|   +-- Territoire de Belfort
|   +-- Yonne

+-- Typologie
|   +-- Lieu d'information et d'accès aux droits
|   +-- Lieu de formation
|   +-- Lieu de médiation publique
|   +-- Lieu de médiation et de fabrication
|   +-- Lieu de travail et de collaboration
|   +-- Tiers-lieu


+-- Label
|   +-- APTIC
|   +-- Charte régionale des tiers-lieux
|   +-- France Tiers Lieu
|   +-- Maison de Services Au Public
|   +-- Maison France Services
|   +-- Nièvre médiation numérique
|   +-- Réseau Dijon métropole
|   +-- Réseau inclusion numérique Chalon 


+-- Modalités d'accompagnement
|   +-- En autonomie
|   +-- Accès libre avec accompagnement
|   +-- Accompagnement individuel sur rendez-vous
|   +-- Accompagnement en groupe sur inscription
|   +-- Atelier de réparation informatique

```

## mode fiche sur carte

Chaque fiche que l'on retrouvera en cliquant sur un point de la carte présentera :
```

|   +-- Nom du lieu
|   +-- Adresse et ville
|   +-- Téléphone
|   +-- Courriel
|   +-- Site internet
|   +-- Accessibilité
|   +---- [pictos correspondant]

```
## Mode liste

Le mode liste aura les entrées suivantes :
```
+-- tableur
|   +-- détails renvoyant vers la page de présentation dédiée (cf fiche détaillée)
|   +-- Nom du lieu
|   +-- Ville
|   +-- Téléphone
|   +-- Site internet
```
## Mode fiche détaillée

Le mode fiche détaillée aura les entrées suivantes :
```
+-- encadré 1
|   +-- Nom du lieu
|   +-- Adresse et ville
|   +-- Téléphone
|   +-- Courriel
|   +-- Site internet
|   +-- Accessibilité
|   +---- [pictos correspondant] 

+-- encadré 2
|   +-- [image]
|   +-- Labels
|   +---- label 1 / label 2

+-- encadré 3
|   +-- Tarifs
|   +---- Tarif 1 / Tarif 2
|   +-- Publics
|   +---- Public 1 / Public 2
|   +-- Modalités d’accompagnement
|   +---- Mode 1 / Mode 2

+-- encadré 4
|   +-- Horaires d’ouverture
|   +---- Lundi :
|   +---- Mardi :
|   +---- Mercredi : 
|   +---- Jeudi : 
|   +---- Vendredi :
|   +---- Samedi :
|   +---- Dimanche : 
