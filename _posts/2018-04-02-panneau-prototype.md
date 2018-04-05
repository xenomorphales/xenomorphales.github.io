---
layout: post
title: Le panneau domotique - prototype
author: elioty
---

Un prototype pour le panneau domotique de la Coupe de robotique de France 2018 a été réalisé. Il s'agit d'un simple chenillard de LED au couleur de l'équipe (vert ou orange cette année). Le résultat en vidéo :

<div class="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/LXebhTbtAUY" frameborder="0" allowfullscreen></iframe>
</div>

Le prototype utilise une Arduino Mega 2560 et trois cartes d'Adafruit embarquant un TLC59711 (driver de PWM utilisé ici pour les LEDs) interfacées en SPI.
Reste maintenant à faire un montage plus propre et respectant les contraintes en terme de dimension imposées par le règlement, ainsi que la partie alimentation avec le cable se connectant à l'interrupteur de la table.
