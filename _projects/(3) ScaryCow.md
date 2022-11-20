---
name: Scary Cow
tools: [C++, DirectX11, PhysX, HLSL, Git]
image: ../assets/grotte_scarycow.png
description: Jeu réalisé sur un moteur maison par 4 personnes. Le joueur incarne un fermier qui doit s'enfuir car ses vaches le poursuivent !
---

# Scary Cow

## Le jeu
**Scary Cow** est un jeu réalisé lors du trimestre d'automne 2021 à l'Université de Sherbrooke (en groupe de 4). Il a été conçu à l'aide d'un moteur créé de toutes pièces pour l'occasion.

Le but du jeu est d'incarner un **fermier** qui est poursuivi par une horde de **vaches** et qui possède un grappin afin de se **propulser** sur des objets prévus à cet effet. La difficulté de la horde est réglable mais si celle-ci nous atteint la partie est perdue !

Pour s'entrainer il existe aussi un mode fantôme où l'on peut affronter nos précédentes parties et même partager les nôtres avec nos amis.

{% include elements/video.html id="XSY4ZI9PMpw" %}

## Tâches réalisées
- Import des objets (terrain, modèles 3D)  
- Gestion de la physique et des collisions  
- Shaders HLSL  
- Affichage des sprites et billboards  
- UI (menus et navigation)  
- Création de la horde  

{% capture carousel_images %}
../assets/menu_sc.png
../assets/menu_sc2.png
../assets/grotte_scarycow.png
../assets/arrivee_sc.png
{% endcapture %}
{% include elements/carousel.html %}
