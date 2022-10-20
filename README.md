# Localib

## Description

Ce repository centralise les parties front et back du projet Localib.
Localib est un projet de gestion des locations de véhicules en 3 tiers (Présentation, Métier, Persistance). Il me sert de base (relativement simple) pour implémenter des nouvelles technologies et techniques de développement pour mon apprentissage personnel.

## Strucure du projet

[/front][repo-front] contient la partie présentation (frontend)  
[/back][repo-back] contient la partie métier (backend)

## Lancer le projet

### Sans submodules

Référez-vous au README des sous projets [/front][repo-front] et [/back][repo-back].

### Avec les submodules

Commande tout en un (clone et mise à jour des submodules):

```bash
git clone --recurse-submodules https://github.com/CheeseWolt/Localib
```

**Si ça ne marche pas**

Cloner ce repo:

```bash
git clone https://github.com/CheeseWolt/Localib
```

Vous aurez ainsi une structure de l'app *vide*.

Initialiser les submodules:

```bash
git submodule init
```

Mettre à jour les submodules (et remplir la structure):

```bash
git submodule update
```

## Contributions

Vous voyez une feature qui manque? Vous avez une idée d'amélioration? Une suggestion?

Alors n'hésitez pas à m'en faire part dans les [issues](https://github.com/CheeseWolt/Localib/issues)


[repo-front]: https://github.com/CheeseWolt/localib-front
[repo-back]: https://github.com/CheeseWolt/localib-back