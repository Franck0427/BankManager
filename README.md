# Gestionnaire de Banque (BankManager)
# Auteur
Développé par SEKA ACHI FRANCK - Étudiant PIGIER CI, Licence 3 (Réseau Génie Logiciel).
## Description
Ce projet Java est une application de gestion bancaire simplifiée développée dans le cadre de l'UE "Projet Informatique II". Il illustre les concepts fondamentaux de la **Programmation Orientée Objet (POO)** tels que l'héritage, l'encapsulation et la structuration de classes.

## Fonctionnalités
L'application permet de manipuler trois types de comptes bancaires distincts héritant d'une classe mère commune :
- **Compte Courant (`CompteCourant`)** : Gère un solde et une limite de découvert.
- **Compte Épargne (`CompteEpargne`)** : Gère un solde d'épargne.
- **Certificat de Dépôt (`CertificatDepot`)** : Gère un solde spécifique pour le dépôt à terme.

## Structure du Projet
- `CompteBancaire` (Classe mère) : Définit les attributs communs `numeroCompte` et `solde`.
- `CompteCourant`, `CompteEpargne`, `CertificatDepot` (Classes filles) : Étendent la classe mère via l'héritage (`extends`).
- `Main` : Classe de test permettant d'instancier les objets et de manipuler les données.

## Prérequis
- **JDK** : Version 21 ou supérieure recommandée.
- **IDE** : IntelliJ IDEA .

## Installation
1. Clonez ce dépôt sur votre machine locale 

Assurez-vous que le SDK du projet est configuré sur Java 21.

Exécutez la classe Main.java pour tester l'application.
