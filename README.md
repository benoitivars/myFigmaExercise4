# Plan de bataille

Nous sommes lundi soir,e t je décide de reprendre ce travail depuis le début. J'ai bien au quelques idées, de bonnes intuitions, mais voir tout le travail en un coup m'a intimidé et m'a donné l'impression de devoir articuler tout à la fois, comme si on emboitait toutes les pièce d'une maquette en même temps.

Non, en fait il faut partir

* en trois temps
* en trois c-volets

## Trois temps

Je fais le pari qu'il faudrait coder ```<head>```, ```<main>``` et ```<section``` séparément, comme un plan Lego nous fait monter le comico de Lego City en différentes parties : le garage, le hall d'entrée, les voitures, ... ici, je veux coder en trois parties.

La question que je me pose d'avance est : vais-je me planter ou non, pour les classes communes auxquelles j'aurais mis des attributs différents ? EN vrai, j'en sais rien. Mais je veux essayer. Puis, ça me fera réviser les bit branch.

### Trois volets

En prenant le temps d'y penser et en regardant le figma, il y a en fait trois volets : les attributs, variables, et caractéristiques communes aux deux Queries, et les spécificités propre à chacune des deux QUeries : portable et plus gros que portable.

### Idée de travail

Ce soir, je pense surtout bosser sur une feuille A4, pliée en neuf, en trois sur trois :

* horizontalement pour mes trois sections
* verticalement pour le code commun et les Queries

Si je tiens bon d'ici cette vue du champ de bataille, peut-être que je tente ce soir de faire le header.

## Header

J'ai vaincu ! Ça n'a pas été une partie d eplaisir, mais ma méthode porte ses fruits. Seulement, je ne maitrise pas encore l'écriture "instinctive" d'un menu comme Henrique nous l'a montré, mon truc de base étant de faire un div avec vlà les classes pour les p, et de display flex l'ensemble, en précisant les gap. 

Là, j'ai dû employer une autre méthode plus expérimentale pour moi, et grandement m'inspirer du boulot de Henrique, ce qui me frustre. De plus, ce code me donne l'impression d'être plus lourd, avec plus de portes ouvertes aux instructions contraires, ou écrites au mauvais emplacement. J'en parlerai avec lui :blush:

## Mergin header et main

Première expérience de merging pour ma part, qui pour ma aprt ne fut pas aussi dure que redouté.

Une grande difficulté que j'ai eu, est de me rendre compte que je n'ai aps eu les mêmes pratiques sur les trois branches pour organiser mon code CSS. 

Ensuite, une autre difficulté fut de naviguer dans le correcteur de conflits, qui pour un projet aussi gros (enfin, gros pour mon expérience, ma remarque doit probablement faire ricanner des devs chevronnés), ne fut pas chose facile : de minuscules fenêtres, des centaines de lignes de code et VSCode qui me dit en substance "vas-y copain, je te regarde faire !".

Ce qui m'a beaucoup aidé, c'est le conseil de Yassine, d'utilliser un simple ficher .txt à l'arrache à côté où coller les bouts de codes corrects. Maintenant, ça a un petit côté "maroufleur du code", mais ça marche... pour l'instant !

## Mergin main (header + body) et section

Premier point : j'ai pris le taureau par les cornes, ai jarté toutes les mentions des fontes sans discrimination, originales et edondantes, pour directement aller chercher sur Google FOnts (qui avait sauvé mes préférences) ce dont j'ai besoin. J'ai du CSS à cheacker et qui me prendra bien assez la tête comme ça que pour le faire victimiser par des link à des polices de caractère.

Maintenant, le reste du mergin, pour le CSS a été moins relou que prévu ! Quelques copiés-colés au bon endroit et ça tient la route !

## Correction Header

J'ai bien alligné le header comme je devais et voulais, en relisant le code de Henrique de l'exercice FIgma 3 !