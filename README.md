# ZAD-X75-A-2021-2022
Projet ZAD d'e-commerce


## Abstract
e-commerce pour une boutique, un vendeur

## Objectif
indépendant des produits, capable de vendre les catégories suivantes:
- bière
- décoration
- software
- matériel informatique
- plante
- equipement de sport


## Technologies
- HTML 5 / CSS 3 / JS / PHP 8.0 / MySQL 8.0 (ou MariaDB)
- Framework CSS: Bootstrap
- Vanilla Javascript / JQuery


## Outils
- Adobe XD pour les maquettes (figma, balsamic, papier/crayon)
- GitHub pour le code
- IDE au choix: SublimeText, VS, Atom, phpStorm
- XAMPP (ou autre stack)
- phpMyAdmin


## Fonctions MUST
Voir <strong>fichier</strong> tabulé (fonctions.ods)

### Recherche/Filtre/Liste
	ANTHONY
Quoi: 
- Permet d’afficher une liste d’articles correspondant à la recherche de l’utilisateur. L’application de filtres permet de trier les articles par catégories.
  
Pourquoi: 
- Permet au client de trouver plus facilement les articles qu’il recherche parmi la liste des produits proposé par la plateforme.
 
Comment: 
- Afficher une barre de recherche ou l’utilisateur pourra entrer le nom de l’article qu’il souhaite consulter.
- Elle devra est en tête du site et devrait toujours être accessible partout sur le site. Le site affichera l’article ou des produits similaires. 
- Si l’utilisateur n’a pas d’article à rechercher ou souhaite obtenir une recherche plus précise, il peut toujours sélectionner différents types de produits à l’aide des filtres/catégories. 
- Pourra rechercher des articles directement dans une catégorie.
Lorsque l’utilisateur utilisera la fonction de recherche, le site affichera l’article ou des produits similaires sous la forme d’une liste. 

	ALEXIS
- Quoi ? Une zone de recherche et des filtres pour avoir une liste de produits plus pertinente selon la recherche du visiteur

- Pourquoi ? Pour facilité la recherche de produit cherché par le visiteur.

- Comment ? Suivant la catégorie de produit ou la recherche du visiteur, le filtre nous proposera des critères comme le prix, la taille, la couleur, … À choisir en fonction du sujet du site, ceux-ci seront sélectionnables grâce à des menus déroulant, checkbox, choix du prix. (prix min/prix max)

### Intéractions

### Réputation
Quoi: 
Pourquoi:
Comment:

### Panier/Commande
Quoi: page présentation pour les produits ajoutés au panier
Pourquoi: 
- permet de consulter/modifier la selection de produits a acheter
- permet de voir le total de la commande
- permet d'entrer un code promo
- permet de passer la commande

Comment on entre:
- les produits ont un CTA "ajouter au panier"
- un bouton dans le header du site (accessible sur toutes les pages)

Ou est ce qu'on sort:
- page de confirmation de commande


### Meilleures ventes

### Mode nuit & couché de  soleil

### Page produit
Quoi: presentation du produit
- nom du produit
- image
- description
- categorie(s)
- nombre de ventes 
- commentaires de satisfaction (avis)
- (les) prix, les promos
- produits suggérés (recommandations, ventes croisées)
- ajouter au panier (avec choix quantité)
- stock, disponibilité
	
Pourquoi:
Présenter les informations nécessaire pour encourager à l'achat (conversion)

Comment:
- barre de recherche
- page accueil (produits recommandés)
- lien direct
	
	


## Fonctions SHOULD

### Recommandations
Quoi:
Montrer des produits qui pourraient plaire aux clients

Pourquoi:
Proposer des produits adaptés aux attentes de l'utilisateur

Comment:
- Visible dans le profil>historique (de consultation des produit) de l'utilisateur.
- En lien avec les informations collectées sur l'utilisateur liées aux pages consultées qu'il consulte.

### Personnalisation

Quoi: 
permet de personnaliser l'interface selon les préférences visuelles de l'utilisateur

Pourquoi:
- Permet de fidéliser le client en lui proposant une interface plaisante
- Permet de désactiver le système "couché de soleil"
- Améliore l'accessibilité en permettant de fixer une taille de police plus grande/petite

Comment:
Donner la possibilité à l'utilisateur d'intervenir sur le design du site via l'espace Profile.

Dans cet espace, un lien "Personnaliser" est disponible, il mène à une page permettant:
	1. de changer la couleur de fond et de texte
	2. de changer la couleur des liens
	3. de changer la police de caractère et sa taille
	4. de (dés)activer le mode "Couché de Soleil"
	5. de (dés)activer le mode Jour/Nuit 

L'utilisateur cochera les cases nécessaire, choisira les couleurs voulues et finira par sauvegarder ses préférences. 

Après la sauvegarde, 
	- un message de confirmation/infirmation apparaîtra
	- on arrive sur la page "Personnaliser" ou "Profile" à décider


### Promotions

Pourquoi :
Permet d'avertir l'utilisateur lorsque une promotion est lancée.

Quoi: 
Offres de prix temporaires sur certains produits ou catégories de produits.

Comment : 
- Bannière cliquable affiché en haut de l'écran et qui nous redirige vers la page ou les produits bénéficiant de la promotion sont affichés
- Décompte ( jours/ heures / minutes )
- Promo affiché sur la page produit

### Profile
### Historique d'achats


## Fonctions NICE
### Interaction clients/clients
### Réputation Produits
### Traduction
### Partage sur réseau sociaux
