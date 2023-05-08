---
title: "Domotique - Mes premiers pas"
author: Bearunik (Mickaël Théraud)
date: May 8, 2023
theme: "night"
transition: "slide"
highlightTheme: "monokai"
---

<!-- .slide: data-background="./images/bg.jpg" data-background-opacity=".3"-->

# Domotique

A la découverte d'un monde sans limite

---

## Sommaire

1. [Un peu de contexte](#contexte)
2. [Le marché des composants](#le-marché)
3. [Les systèmes domotiques existants](#les-systèmes-domotique)
4. [Mes premières expériences](#mes-expériences)
5. [Puis, ça à dérappé...](#plus-loin-que-prévu)

---

## Contexte

Ça faisait longtemps que je souhaitais m'y pencher mais je ne s'avais pas par où commencer...

Jusqu'à l'augmentation du coût de l'électricité ! ⚡

> Oh my god !

--

### Mon besoin

Mon premier besoin était celui de mieux gérer ma consomation électrique.

<img src="./images/contexte/green-energy.png" alt="Energies vertes" height='450'>

--

### Les chantiers

J'ai donc lancé 2 sujets en parralèlles :

- Les panneaux photovoltaique ☀️
- La domotique 🤖

---

## Le marché

Pour commencer mon aventure, j'ai regardé ce qu'il était possible de faire pour analyser ma consomation.

![Les concurrents](./images/marche/concurrents.jpeg)

> Ah ouais... il y a de quoi s'amuser !

--

### Restons focus

Au vu de ce monde hyper vaste, j'ai affiné ma recherche sur plusieurs critères :

1. Constructeurs européen
2. Mesurer finement la consomation
3. Solution durable et modulaire

--

### L'heureux élu

Je suis donc parti chez [**Shelly**](https://www.shelly.cloud/fr/company/about-shelly), c'est la marque phare de l'entreprise **Allterco Robotics**, située en Bulgarie.

<img src="./images/marche/shelly-france.jpeg" alt="Shelly france" height="200px">

Aussi, ils possèdent également une filiale en France.

--

### Mais pourquoi ?!

Le rapport qualité/prix et surtout la flexibilité et la compatibilité des composants.

<img src="./images/marche/shelly.png" alt="Shelly" height="200px">

> Et en plus ça se configure facilement hors de l'app propriétaire !

---

## Les systèmes

Acheter des composants, c'est bien.

Les piloter, c'est mieux.

<img src="./images/systemes/systemes-domotiques.jpeg" alt="Les systèmes domotiques" height="250px">

> Wow ! Là aussi y'a du monde !

--

### Etude rapide

Pour le coup, je n'ai pas perdu beaucoup de temps ici car ça s'est fait au travers de discussions avec d'autres pationnés du sujet 👌.

--

### Le gagant est... 🥁

Etant open source, hyper connu / utilisé et très fortement maintenu je suis parti sur [**Home Assistant**](https://www.home-assistant.io/).

<img src="./images/systemes/home-assistant.png" alt="Home Assistant" height="150px">

--

### Le gros avantage

Voici la phrase qui ma quasiment convaincu instantanément :

> Ce qui est génial avec Home Assistant c'est sa communauté ! En effet, c'est assez rare de ne pas trouver une réponse / un module sur le market répondant à une problématique que tu vas rencontrer.

--

### HA x Raspberry Pi

En fouillant un peu avant de me lancer, j'ai remarqué aussi que l'outil était compabtile avec Raspberry Pi.

<img src="./images/systemes/raspberry.png" alt="Raspberry Pi" height="150px">

> Ça tombe bien, j'en avais une à recycler ! ♻️

---

## Mes expériences

> Allez c'est parti pour l'aventure ! 🤝

--

### Home Assistant 🛠️

On installe [Home Assistant sur la raspberry](https://www.home-assistant.io/installation/raspberrypi/).

--

### Shelly France 🇫🇷

On commande ce qu'il faut :

- Des blocs prises murales
- Des boutons
- Des prises

--

### On paramètre tout bien 👨‍💻

![Configuration Home Assistant](./images/exeperiences/configure.png)

> Magie, ça trouve des trucs tout seul !

--

### Programation de scénarios 🤔

![Scénarios](./images/exeperiences/scenarios.png)

--

### Récupération des metriques 📈

![Metrique energie](./images/exeperiences/analytic-enery.png)

Consomation totale sur une semaine

--

### Récupération des metriques 📈

![Metrique power](./images/exeperiences/analytic-power.png)

Consomation réele sur une semaine

---

## Plus loin que prévu
