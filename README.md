# dsPIC-oscilloscope
Projet d'oscillscope numérique basé sur un dsPIC

## Motivation
Le but principal de ce projet est de fournir un exemple en terme de méthodologie (versioning, tests unitaires, documentation...).
Il doit aussi introduire des notions utiles pour le projet intégré. Certains de ces blocs pourront être réutilisés dans ce dernier.
La réalisation d'un oscilloscope numérique connecté à un PC répond bien à ces buts : 
* c'est un projet suffisamment ambitieux pour illustrer les avantages d'une méthodologie de développement
* la plupart de ces fonctionnalités seront utiles dans le projet intégré : 
  * la mise en forme d'un signal analogique
  * la numérisation de ce signal au moyen d'un convertisseur analogique-numérique (ADC : Analog to Digital converter)
  * l'utilisation d'une communication USB entre un micro-contrôleur et un PC (très utile pour le debug)

## Description générale du projet
On veut donc réaliser un système à micro-contrôleur qui sera piloté par un PC au travers d'une connexion USB.  Ce système fera l'acquisition d'un signal analogique à une fréquence fixée par le PC.
Les échantillons obtenus seront envoyés au PC qui les affichera.

## Evolution du projet
[L'évolution du projet](https://github.com/miosee/dsPIC-oscilloscope/wiki/Evolution-du-projet) est décrite dans le wiki. Il contient également une explication détaillée des différents blocs fonctionnels du système.
