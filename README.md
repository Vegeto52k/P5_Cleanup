# ✅ Todoc – Application de gestion de tâches

## 🎯 Objectif
Finaliser une application Android de gestion de tâches pour l’entreprise Cleanup en implémentant la persistance des données.

---

## 🧠 Contexte

Projet réalisé dans un contexte professionnel simulé pour **Cleanup**, une agence de nettoyage de locaux commerciaux.

L’application **Todoc** permet aux collaborateurs de gérer leurs tâches quotidiennes.  
L’existant proposait déjà les fonctionnalités principales de gestion des tâches, mais la persistance des données n’avait pas été développée.

La mission consistait donc à rendre l’application exploitable en conditions réelles en ajoutant une base de données locale et en mettant à jour l’architecture associée.

---

## 🧪 Technologies utilisées

- Java
- Android SDK
- SQLite / Room
- JUnit (tests unitaires)
- Espresso (tests instrumentalisés)
- Git / GitHub

---

## ⚙️ Fonctionnalités

### Fonctionnalités existantes
- Affichage de la liste des tâches
- Ajout d’une tâche
- Suppression d’une tâche
- Tri des tâches par projet
- Tri des tâches par date de création

### Fonctionnalités finalisées / implémentées
- ✅ Persistance des données via une base locale
- ✅ Sauvegarde des tâches
- ✅ Sauvegarde des projets
- ✅ Mise à jour du comportement de l’application avec Room
- ✅ Gestion de l’affichage d’un état vide si aucune tâche n’est présente

---

## 🗃️ Base de données

Le projet intègre une base de données locale afin de conserver les données même après fermeture de l’application.

### Objectifs de cette implémentation
- structurer les données
- conserver les tâches et projets
- préparer l’évolution future de l’application

### Éléments mis en place
- entités représentant les tâches et les projets
- schéma de base de données
- couche d’accès aux données
- intégration de Room dans l’architecture existante

---

## 🧱 Architecture

Le projet repose sur une architecture Android structurée autour :

- d’un modèle de données clair
- d’une couche de persistance
- d’une séparation entre logique métier, données et interface

Des livrables de conception ont également été produits :
- **modèle physique de données (MPD)**
- **diagramme de classes**
- **diagramme de cas d’utilisation**

---

## 🧪 Tests

- Mise à jour des tests unitaires pour intégrer la persistance
- Mise à jour des tests instrumentalisés
- ✅ Tous les tests passent avec succès

---

## 📱 Interface utilisateur

L’application permet :
- de visualiser les tâches associées à différents projets
- d’identifier rapidement un projet grâce à une couleur dédiée
- d’ajouter une tâche en l’associant à un projet
- de supprimer une tâche
- de trier les tâches selon différents critères

Elle reste compatible avec :
- smartphones et tablettes
- modes portrait et paysage
- Android 5.0 (API 21) et versions supérieures

---

## 🔐 Build release

Le projet inclut également un travail autour de la préparation d’une version de production :

- génération d’un **APK signé**
- construction d’une version **release**
- **obfuscation** du code pour renforcer la protection du projet

---

## 🚀 Lancer le projet

1. Cloner le repository :
```bash
git clone https://github.com/tonpseudo/nom-du-repo.git
