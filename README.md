# Week n°6 on Day n°1/2 - THP by Team BDX - @massimo - THPBrite-like v2.0

## Projet du jour :

Le projet du jour consiste a construire une application compatible Heroku, qui permet de gérer des évènements sur une plateforme à la eventbrite-like. Cette fois-ci, il faut utiliser les gems "devise" (gestion de sessions et utilisateurs), et "Stripe" (gestion de paiements).

## Pré-requis et installation :

1 - Veuillez svp, vous relever de votre PLS.

2 - Veuillez cloner ce repo sur votre machine avec la commande suivante (le dossier créé s'appelera "W6D2_TeamBDX_2_THPBrite-like") :

```
  $ git clone https://github.com/iMassim0/W6D2_TeamBDX_2_THPBrite-like
```

3 - Se rendre dans le dossier souhaité, et effectuer la commande suivante pour initialiser le fonctionnement :

```
  $ bundle install --without production && rails db:migrate
```

## Fonctionnement de l'application :

Soit en la lançant en local sur votre machine, pour cela, lancez depuis votre terminal, lorsque vous êtes dans le dossier courant :

```
  $ rails server
```

Puis vous rendre à l'adresse suivante :
```
  @ http://localhost:3000/
```

Ou alors, vous pouvez directement vous rendre à l'adresse déployée ici :
```
  @ https://damp-woodland-88264.herokuapp.com/
```

**NOTA : $ = terminal || > = console rails || @ = internet browser**

## Conditions de test de l'application pour les corrections

Pour faciliter la correction, je me suis arrêté pour cause de PLS d'OR 2018 après 2 jours intenses avant le déploiement de la gem "stripe". L'affichage des éléments où l'utilisateur en cours participe aura eu raison de moi ... Merci pour la correction ;).

#Désopadéso - #LaMandàMandit - #Maman - #KeskiaKeskiaToiTuMengraines?

Ne pas hésiter à vous rendre dans la console rails pour créer des instances de "User" et de "Event" dans la console :
```
  $ rails console
```

## Pré-requis

**Ruby 2.5.1**

**Bundle 1.16.1**

## Contributeur

@massimo - Maxime FLEURY

*Avec l'aide précieuse de M. @bab*

<p align="center">
  <img src="THP_BDX.png"/>
</p>
