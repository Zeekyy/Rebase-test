
# Git Rebase - Guide Rapide

Le rebasage consiste à déplacer vers un nouveau commit de base ou à combiner une séquence de commits. Le rebasage est plus utile et facilement visible dans le contexte d'un workflow de branche de fonctionnalité. Vous pouvez visualiser le processus général comme suit :


![image](https://github.com/Zeekyy/Rebase-test/assets/75806615/dc0169d2-7d00-4b39-abf0-3a773b347e61)


Au niveau du contenu, le rebase consiste à changer la base de votre branche d'un commit vers un autre, donnant l'illusion que vous avez créé votre branche à partir d'un commit différent. En interne, Git réalise cette tâche en créant de nouveaux commits et en les appliquant à la base spécifiée. Il est important de comprendre que, même si la branche semble identique, elle est composée de commits tout nouveaux.


# Git Rebase - Guide Rapide

## Introduction

Le rebasage (rebase) est une opération Git qui permet de fusionner une branche avec une autre en réappliquant les commits de la branche actuelle sur la branche cible. Cela diffère de la fusion traditionnelle qui crée un nouveau commit de fusion.

## Avantages du Rebasing

1. **Historique Linéaire :** Le rebasage crée un historique linéaire, ce qui le rend plus lisible que l'historique de fusion complexe.

2. **Évite les Commits de Fusion Redondants :** Les commits de fusion sont éliminés, ce qui rend l'historique plus propre.

3. **Facilite la Résolution des Conflits :** En résolvant les conflits au fur et à mesure des commits, il est plus facile de gérer les conflits.

https://www.youtube.com/watch?v=F2LVk8zjAa0&ab_channel=TomAgro

Rebase: 

![image](https://github.com/Zeekyy/Rebase-test/assets/75806615/e335b213-e89f-4453-b70c-a42fa426c8e1)

Merge:

![image](https://github.com/Zeekyy/Rebase-test/assets/75806615/3e97dc1e-236c-4af8-bd99-b1c44b69452e)


