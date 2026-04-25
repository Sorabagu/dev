# Dev

**Dev** est une application macOS native dédiée à la création et à l’itération sur des pages et petits sites web. Elle rassemble l’édition de code, la prévisualisation, la navigation dans les fichiers et le débogage dans une seule interface, pour aller droit au but sans la complexité d’un IDE généraliste.

## À quoi sert-il ?

- **Prototyper** rapidement en HTML, CSS et JavaScript, avec retour visuel immédiat.
- **Structurer un mini-projet** (fichiers, dossiers) sans quitter l’app.
- **Débugger** le rendu et le code grâce à une console intégrée et un suivi des requêtes réseau.
- **Tester le responsive** (bureau, tablette, mobile) depuis la fenêtre de prévisualisation.
- **Démarrer un projet Vite + React (TypeScript)** : squelette généré, `npm install` proposé si Node est disponible, prévisualisation via le serveur de dev Vite.

En résumé : un environnement ciblé *front web* sur Mac, du fichier unique au petit dépôt de fichiers, avec un mode projet HTML classique ou une base **Vite + React** selon le type de création.

## L’éditeur

- **Coloration syntaxique** (Monaco) pour HTML, CSS, JavaScript, JSON, Markdown et d’autres formats courants.
- **Onglets** pour plusieurs fichiers ouverts, avec indicateur de modifications non enregistrées.
- **Numérotation des lignes** et thèmes d’éditeur **clair / sombre**, avec possibilité d’**ajuster le thème par type de fichier** (HTML, CSS, JS, etc.).
- **Raccourcis** pour la sauvegarde, la navigation par onglets, annuler / refaire, copier-coller, etc. (voir ci-dessous).

## Prévisualisation

- Mise à jour **en direct** : les changements dans l’éditeur se reflètent dans la prévisualisation **sans rechargement manuel** ni obligation de sauvegarder d’abord.
- **Fenêtre de prévisualisation** détachable / redimensionnable, pratique sur un second écran.
- **Modes responsive** (bureau, tablette, mobile) pour valider l’apparence à différentes largeurs.
- **Mode inspection** : pointer un élément dans l’aperçu met en évidence le code correspondant dans l’éditeur.

## Explorateur de fichiers

- Arborescence du projet, **création de fichiers** (menu contextuel), ouverture d’un fichier en un clic.
- Bascule **affichage / masquage** de l’explorateur (**⌘B**).

## Console développeur

- Logs **info**, **avertissements** et **erreurs**, avec **horodatage** et **dédoublonnage** (compteur quand le même message se répète).
- **Recherche / filtrage** dans les messages.
- Onglet **réseau** : méthode, URL, statut, type, taille, durée.
- **Effacement** de la console pour repartir de zéro.  
  Affichage / masquage de la console : **⌘J**.

## Projets

- **Écran d’accueil** : nouveau projet, ouvrir un dossier, **projets récents** (nom, emplacement, dernière ouverture).
- **Types de projet** : page **HTML + CSS + JS** (fichiers de base + métadonnées de projet) ou **TypeScript / React (Vite)** avec structure Vite et prévisualisation via le port de dev.
- Ouverture de **dossiers existants** contenant notamment un `index.html`, même s’ils n’ont pas été créés dans Dev (rétrocompatibilité des projets sans fichier de métadonnées : traités comme des projets HTML).

## Personnalisation de l’interface

- Thème général (en-tête, barres latérales, bordures) pour coller à votre habitude de travail.
- **Interface multilingue** (sélecteur de langue ; option « système » possible).

## Raccourcis et navigation (macOS)

| Raccourci | Action |
|-----------|--------|
| ⌘S | Enregistrer le fichier en cours (⇧⌘S enregistre **tous** les fichiers modifiés) |
| ⌘B | Afficher / masquer l’explorateur |
| ⌘J | Afficher / masquer la console |
| ⌘W | Fermer l’onglet actuel |
| ⇧⌘H | Revenir à l’écran d’accueil (menu *Dev*) |
| ⌘Q | Quitter l’application |

*Les commandes d’*Édition* standard du menu macOS s’appliquent dans l’éditeur (annuler, refaire, copier, coller, tout sélectionner, etc.).*

## Barre de statut

Affiche le projet en cours, le fichier actif, le type de fichier et, en mode inspection, des indications utiles (par ex. nombre de lignes concernées).

---
