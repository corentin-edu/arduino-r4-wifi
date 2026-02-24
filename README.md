# 🚀 Arduino Uno R4 WiFi - Web Dashboard Control

[![Télécharger le projet](https://img.shields.io/badge/TÉLÉCHARGER-Code%20Complet%20(ZIP)-blue?style=for-the-badge&logo=github)](https://github.com/corentin-edu/arduino-r4-wifi/archive/refs/heads/main.zip)

**Projet de fin de séquence - Session 2025/2026** **Développé par :** Corentin PORCQ (Classe : 2TNE1)

---

## 📝 À propos du projet
Ce projet consiste en la création d'un **système domotique miniature** piloté par une interface web interactive. L'objectif est de transformer une carte Arduino Uno R4 WiFi en un serveur capable de gérer des sorties physiques (LEDs) et des entrées capteurs (Température/Humidité) de manière sécurisée.

### 🤖 Note Pédagogique
Dans le cadre de ce projet, **l'utilisation de l'intelligence artificielle a été autorisée pour la programmation** afin d'accompagner le développement et la compréhension du code.

## 🛠 Matériel utilisé
* **Microcontrôleur :** Arduino Uno R4 WiFi.
* **Capteur :** DHT22 (Température et Humidité).
* **Actionneurs :** 5 LEDs + 5 Résistances de 220Ω.
* **Logiciel :** Arduino IDE avec bibliothèques `WiFiS3` et `DHT sensor library`.

## 📂 Contenu du dépôt
* `arduino_code.ino` : Le code source principal.
* **`plan-installation.pdf`** : **Le guide complet à suivre pour l'installation et le câblage.**

---

## 📖 Comment l'installer ?

> [!IMPORTANT]
> **Pour mettre en service le projet, veuillez impérativement suivre les étapes détaillées dans le fichier `plan-installation.pdf` présent dans ce dépôt.**

### Résumé de la procédure :
1.  **Téléchargement :** Cliquez sur le bouton bleu en haut de cette page pour récupérer l'archive ZIP.
2.  **Câblage :** Connectez les 5 LEDs (Pins 9 à 13) et le capteur DHT22 (Pin 6) comme indiqué dans le PDF.
3.  **Configuration :** Modifiez les variables `ssid` et `pass` dans le code avec vos identifiants WiFi.
4.  **Téléversement :** Utilisez l'Arduino IDE pour envoyer le code vers la carte.
5.  **Accès :** Récupérez l'adresse IP via le moniteur série et ouvrez-la dans votre navigateur.
6.  **Validation :** Tapez `y` dans le moniteur série pour autoriser votre propre connexion.

---

## ⚙️ Détails Techniques
L'interface web est directement intégrée dans le code Arduino. Elle utilise du JavaScript pour gérer les requêtes HTTP asynchrones, permettant de contrôler les LEDs sans recharger la page. Le projet supporte également des raccourcis clavier pour un contrôle fluide.

---
*Projet réalisé dans un cadre pédagogique pour démontrer la maîtrise des serveurs web embarqués sur microcontrôleur.*