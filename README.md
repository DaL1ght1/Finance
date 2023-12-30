# Projet Finance

## Table des matières

- [À propos du projet](#à-propos-du-projet)
- [Fonctionnalités](#fonctionnalités)
- [Tableau des opérations](#tableau-des-opérations)
- [Persistance des données](#persistance-des-données)
- [Preuve](#preuve)
- [Contribution](#contribution)
- [Licence](#licence)

## À propos du projet

Le "projet finance" est une application web qui permet aux utilisateurs de créer un 'compte épargne' et d'effectuer diverses opérations bancaires telles que des dépôts et des retraits. Chaque opération est enregistrée dans un tableau HTML dynamique qui ajoute une ligne à chaque nouvelle transaction.

## Fonctionnalités

- Création d'un compte épargne.
- Réalisation d'opérations de dépôt et de retrait.
- Affichage des opérations dans un tableau HTML dynamique.

## Tableau des opérations

Le tableau des opérations enregistre les informations suivantes pour chaque transaction :

- Date de l'opération
- ID de l'opération
- Nom du titulaire du compte
- Type d'action (dépôt ou retrait)
- Solde
- Date de valeur
- Nombre de jours
- Taux
- Intérêt

## Persistance des données

Les données des opérations sont stockées temporairement et seront perdues lors du rechargement de la page. Pour une persistance des données, une solution de stockage côté serveur ou l'utilisation de la technologie localStorage côté client pourrait être implémentée.

## Preuve 

Pour prendre une idée sur le foncionnement de ce site web n'hesitez pas a télécharger le video `Preuve.mp4`.

## Contribution

Les contributions à ce projet sont les bienvenues. Veuillez suivre les étapes suivantes pour contribuer :

1. Forkez le dépôt.
2. Créez une branche pour votre fonctionnalité :
   ```Git
       git checkout -b feature/mafonctionnalite
6. Committez vos modifications :
   ```Git 
    git commit -am 'Ajout de ma fonctionnalité'
10. Poussez la branche :
    ```Git
     git push origin feature/mafonctionnalite
14. Ouvrez une Pull Request.

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](https://github.com/DaL1ght1/Finance/blob/main/LICENSE) pour plus de détails.


