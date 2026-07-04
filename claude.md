# systeme_manon_payoux-hugo_caillol

Ce repository documente le système d’enchère et de signalisation au jeu de la carte de la paire Manon Payoux - Hugo Caillol

Ce système est structuré autour de quelques principes clés :

Ouvertures :

- Meilleure mineure
- Majeure 5e
- 1SA fort : 15–17H
- 2♣ Kokish : pour toutes les mains forcing de manche irrégulières et toutes les mains fortes régulières (22H et+)
- 2♦/♥/♠ faibles : unicolores faibles (6+ cartes)

Signalisation à Sant Atout :

- Entame 4e meilleure
- Appel direct
- Defausse lavinthal
- Appel de Smith

Signalisation à l'atout :

- Entame pair-impair
- Appel direct
- Defausse lavinthal

L’ensemble est présenté dans un seul fichier .md pour faciliter la relecture, les modifications et le versioning collaboratif.

Les changements se font via pull request avec validation mutuelle.

## Pour Claude :

- Le fichier système-manon-hugo.md est le fichier principal de ce repo.
- Il doit être aussi lisible que possible quand affiché en .md.
- On privilégiera l'usage de séquénces détaillées ligne par ligne aux tableaux qui peuvent poser des problèmes d'affichages et sont plus embêtants à copier coller.
- Lors d'ajouts ou modifications du document, ne modifie JAMAIS la signification d'une enchère.
- Pour remplacer un bloc de plusieurs lignes (ex. une table entière), l'outil Edit échoue souvent silencieusement sur ce fichier (probable souci d'encodage sur les caractères accentués/apostrophes courbes). Si Edit échoue une ou deux fois sur un même bloc, ne pas insister : relire le fichier en entier et le réécrire avec Write plutôt que de multiplier les tentatives.

Notation d'une enchère :

- Symbole de couleur collé au chiffre, sans espace : 1♣, 2SA, 3♦ (jamais 1 ♣ ou 1C).
- Alternative en majeure/mineure générique acceptée quand la couleur précise importe peu : M (majeure), m (mineure), X (contre), XX (surcontre).
- x minuscule après un chiffre (ex. 3x) : nouvelle couleur générique quelconque, à distinguer de X majuscule qui reste réservé au contre (XX au surcontre).
- Options groupées avec / sans espace : 2♥/♠, 3♣/♦ (= « 2♥ ou 2♠ », signification commune donnée une seule fois).
- Séparateur : entouré d'un espace de chaque côté entre l'enchère et sa signification : 1SA : 15–17H.
- Zones de points en tiret cadratin sans espace, suffixe H collé : 15–17H, jamais 15-17 H.

Rappel d'une séquence complète

- Introduite par Après **...** : (gras, deux-points après un espace), les enchères séparées par - ou – (tiret cadratin) avec espaces des deux côtés : Après **1♣ - 1♦** :.
- Utilisée juste avant une table ou une liste qui détaille les enchères disponibles à ce point précis de l'auction.
- Pour une séquence longue de relais répétés, le tiret cadratin – est privilégié (1SA – 2♦ – 2♥ – 2SA – 3♣ – 3♦) — à uniformiser dans le nouveau doc puisque le fichier source mélange - et –.

Deux formats pour détailler les réponses

- Table | Enchère | Signification | quand toutes les réponses possibles à une seule enchère du partenaire sont listées à plat (cas le plus fréquent, ex. réponses à l'ouverture).
- Liste à puces imbriquée quand l'arborescence a plusieurs niveaux de relais/redemandes : chaque niveau supplémentaire de l'auction = un cran d'indentation de 2 espaces, sans répéter Après ... : à chaque niveau :

- 1♠ : relais avec mains mini
  - 1SA : régulier
    - 2♣ : 5♣ (type canapé)

Cas particuliers

- Enchère artificielle définie une fois : blockquote juste sous le titre de section, avant la table : > 1♦ = texas ♥ (4+).
- Convention nommée renvoyée à plus tard : _ après l'enchère dans la table (2♣ | Gazzilli_), puis développée dans une section dédiée plus bas (# Gazzilli, ou Après **1♥ - 1♠ - 2♣** :).
- Ligne isolée pour un cas particulier trop profond pour justifier une arborescence : toute la séquence sur une ligne, suivie de : puis la signification : 1♣ - 1♥ - 2♣ - 2♦ - 2♥ - 2♠ : 6♠ sans 4♥.
- Abréviations standard : H (points d'honneur), NF (non-forcing), FM (forcing de manche), BW (Blackwood), 2/1.
- --- en ligne seule pour séparer les sous-sections (une par « Après ... » ou par grande partie).
