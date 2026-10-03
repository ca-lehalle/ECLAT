# ECLAT

> Exemples de Calendriers, Listes et Agendas en TeX.

Réalisés avec un peu d'intelligence biologique et  l'aide de Claude.ai


## Semaine - Week

Une semaine générique.

## Todo

Une liste de todo organisable en 

- missions
- projets
- buts.

## 1 mois - Month

Pour changer de mois, il suffit de modifier trois lignes en haut du fichier. Les noms de jours se recalculent automatiquement :

```
\newcommand{\moisnom}{NOVEMBRE 2026}
\newcommand{\firstwd}{7}   % jour du 1er : 1=lundi ... 7=dimanche
\newcommand{\ndays}{30}    % nombre de jours du mois
```

## 7 mois - Months

Ce sont des mois génériques.
