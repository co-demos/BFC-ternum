# arborescence du site "Cartographie des structures de la médiation numérique en Bourgogne-Franche-Comté"

## équipe 

- Jean-Christophe (typologies, design, jeux de données, data, contenus)
- Bruno Louis (design, contenus, technique)
- Corine (contenus)

## arborescence

```
.
+-- home : page d'accueil avec présentation
+-- La cartographie: vue carte par défaut - niveau de zoom Bourgogne-Franche-Comté
+-- MedNum BFC
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
- Quelles couleurs ? Les trois couleurs principales utilisées sur le site de MedNum BFC sont : #293e86 (bleu foncé), #f24c61 (rouge) et #37bec1 (turquoise).
- Quelles typos? La typo utilisée sur le site de MedNum BFC est Poppins https://fonts.google.com/specimen/Poppins
- Quelle URL ? https://cartographie.mednum-bfc.fr/
- Quel nom pour cette carte ? Cartographie des structures de la médiation numérique en Bourgogne-Franche-Comté
- site uniquement en français, pas de version multilingue

## filtres 
```
Note: on doit pouvoir cocher plusieurs catégories dans chaque filtre et plusieurs filtres ensemble.

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

+-- Labellisation
|   +-- APTIC
|   +-- Espace de coworking
|   +-- FabLab
|   +-- FabLab solidaire Orange
|   +-- France Tiers Lieu
|   +-- Maison de Services Au Public
|   +-- Maison France Services
|   +-- Nièvre médiation numérique
|   +-- PANDA
|   +-- Réseau inclusion numérique Chalon 
|   +-- Réseau Dijon métropole
|   +-- Signataire de la charte des tiers-lieux

+-- Modalités d'accompagnement
|   +-- En autonomie
|   +-- Accès libre avec accompagnement
|   +-- Accompagnement individuel sur rendez-vous
|   +-- Accompagnement en groupe sur inscription
|   +-- Atelier de réparation informatique

## fiche (dans liste) A FAIRE ENCORE

```
Chaque fiche que l'on retrouvera dans liste doit mettre en forme les informations suivantes du tableur
+-- encadré 1
|   +-- image  
|   +-- ville
|   +-- nom du lieu
|   +-- description

+-- encadré 2
|   +-- adresse complète
|   +-- telephone
|   +-- url 

+-- encadré 3
|   +-- typologie
|   +-- publics
|   +-- modèle juridique

```
## mode table

Le tableur aura pour entrées:
|   +-- détails renvoyant vers la page de présentation dédiée (cf fiche)
|   +-- Nom du lieu
|   +-- Adresse du lieu
|   +-- Ville
|   +-- Téléphone
|   +-- Site internet
