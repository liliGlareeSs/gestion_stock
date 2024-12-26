Gestion de Stock
Description
Ce projet de gestion de stock est conçu pour suivre les produits en entrepôt, gérer les entrées et sorties de stock, surveiller les niveaux de stock, et générer des alertes en cas de pénurie ou de dépassement de seuil.

Le projet met en œuvre les concepts de la programmation orientée objet (POO), tels que l'encapsulation, l'héritage, les relations N:M et utilise des technologies comme JDBC pour la gestion de bases de données.

Fonctionnalités
Gestion des Produits :

Ajouter, modifier et supprimer des produits.
Consulter les détails d'un produit.
Gestion des Fournisseurs et Clients :

Enregistrer des fournisseurs et clients.
Associer des fournisseurs aux produits.
Gestion des Commandes :

Créer des commandes pour les clients.
Gérer les articles d'une commande.
Suivi des Stocks :

Surveiller les niveaux de stock.
Détecter les seuils critiques et générer des alertes.
Interface Interactive :

Menu en ligne de commande pour interagir avec le système.
Structure du Projet
src/
models/ : Classes principales (Produit, Stock, Fournisseur, Client, Commande, etc.)
dao/ : Accès aux données avec DAO et JDBC.
services/ : Logique métier et gestion des opérations.
main/ : Point d'entrée du programme.
Technologies Utilisées
Langage : Java
