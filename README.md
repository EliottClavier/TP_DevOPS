# TP DevOPS

Vous trouverez dans ce repository GitHub deux workflows permettant le déploiement sur un environnement de test "on push on develop" et le déploiement sur un environnement de production "on new release".

## Environnements

Les deux environnements sont hébergés sur Firebase hosting:
  - Environnement de test: https://stagingenv-tp-devops.web.app
  - Environnement de production: https://tp-devops.web.app

## Package

Le workflow "on new release" crée un artéfact du repository et publie ce dernier sur le gestionnaire de packages NPM, retrouvable à l'adresse suivante:
https://www.npmjs.com/package/tp_pipeline

## Résumé du projet

Le résumé du projet se trouve à l'adresse suivante:
  - https://flolpb.github.io
