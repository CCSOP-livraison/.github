# CCSOP - PROJECT

**CCSOP**, une plateforme de livraison à domicile après commande auprès de restaurant dévelopé avec Spring Boot & vue.js.

---

## 📌 Table des Matières

1. [Descriptif du Projet](#descriptif-du-projet)
2. [Conception & Modélisation](#conception--modélisation)
3. [Pratiques Git & Commits](#Pratiques-Git--Commits)
4. [Guide utilisateur](#Guide-utilisateur)
5. [Problèmes Connus & Limitations](#problèmes-connus--limitations)

---

## Descriptif du Projet

**CCSOP livraison** est une plateforme web pour commander des repas auprès des restaurants partenaires avec livraison.

Un client peut choisir le restaurant dans lequel il souhaite commander et accéder à sa carte dédiée. Une fois sa commande passée, une livraison est automatiquement créée et proposée aux livreurs. La livraison est clôturée dès lors qu'elle est validée à la fois par le livreur et par le client.

## Conception & Modélisation

L'ensemble des diagrammes du projet généraux du projet - **modèle conceptuel des données (MCD)**, **planification gantt**, **uses cases** et **diagrammes de séquences** - sont disponibles dans le dossier [`.github/doc`](https://github.com/CCSOP-livraison/.github/tree/main/doc).

---

## Pratiques Git & Commits 

### Stratégie de branches (Git Flow)
Le projet s'est basé sur le modèle **Git Flow**. Pour la description complète du fonctionnement des branches, des règles de fusion et du cycle de vie des releases, référez-vous à la spécification officielle : [A successful Git branching model - nvie.com](https://nvie.com/posts/a-successful-git-branching-model/).

> [!IMPORTANT]
> Une fois qu'une branche `feature/` ou `bugfix/` est testée et fusionnée avec succès sur `develop`, elle doit être supprimée du dépôt distant pour maintenir l'historique propre.

### Conventions de commit (Conventional Commits)
L'équipe applique la spécification [Conventional Commits 1.0.0](https://www.conventionalcommits.org/fr/v1.0.0/). Chaque message de commit doit être préfixé par son type :
- `feat:` : Ajout d'une nouvelle fonctionnalité
- `fix:` : Résolution d'un bug
- `docs:` : Modification de la documentation
- `refactor:` : Modification du code sans changement de comportement (restructuration, renommage)

---

## Guide utilisateur  
Vous retrouverez le Guide utilisateur ici : [Guide utilisateur](https://github.com/CCSOP-livraison/.github/blob/main/profile/Guide-utilisateur.md)

---

## Definition of done 
Les fonctionnalités ont été vérifié au travers de la [Definition of done](https://github.com/CCSOP-livraison/.github/blob/main/profile/definition-of-done.md)

