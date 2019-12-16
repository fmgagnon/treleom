## treleom

Ce _patch_ Pure Data traite un signal sonore (originalement pour la guitare) en lui appliquant un effet de tremolo progressif sur une durée donnée jusqu'à un tempo-cible et une amplitude-cible. Cette progression est calculée selon des paramètres réglables.

### Compatibilité

- Ce _patch_ n'a été testé qu'avec Pure Data pour macOS.

### Entrée/Sortie

- Le _patch_ additionne le signal des deux canaux de l'entrée système et émet le même signal dans les deux canaux de la sortie du système.

### Contrôles

![Capture d'écran : contrôles](principal.png?raw=true "Contrôles")

- Le bouton **zéro** remet la progression à zéro.
- La **durée totale** est réglée en secondes.
- Les réglages des **tempi (départ et cible)** sont réglés en bpm.
- La barre horizontale est un indicateur de progression.
- L'interrupteur *croissant* permet d'activer le mode croissant, qui débute avec un tremolo agressif qui arrête progressivement sur un volume constant (1).
