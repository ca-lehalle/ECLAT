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

## 1 mois grille - Month grid

Pour retirer les étiquettes AM et PM tout en gardant les teintes, mettez `\showampmfalse` à la place de `\showampmtrue` en haut du fichier. Les trois couleurs de l'après-midi (`pmpaper, pmcream, pmoff`) se règlent juste en dessous des autres couleurs. Si la différence vous paraît trop forte ou trop faible à l'impression, ce sont elles qu'il faut ajuster.

## 7 mois - Months

Ce sont des mois génériques.
