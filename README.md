# 🐳 Rapport de Projet - Hello MARIO Docker
**Auteur :** Anziz  
**Environnement :** Chromebook (Linux Crostini)

## 📋 Description du Projet
Ce projet consiste à découvrir l'univers Docker en déployant différents conteneurs[cite: 2, 4].

## 🛠️ Jobs Réalisés

### **Job 01 : Premier Conteneur**
* **Commande** : `sudo docker run hello-world`[cite: 18].
* **Résultat** : Docker a récupéré l'image sur la registry officielle et affiché le message de confirmation[cite: 19, 42].

### **Job 02 : Déploiement du jeu Mario**
* **Commande** : `sudo docker run -d -p 4545:80 sevenajay/mario:latest`[cite: 72].
* **Accès** : Le jeu est accessible via le port 4545[cite: 71, 82].

### **Job 03 : Monitoring et Maintenance**
* **Commandes utilisées** :
    * `sudo docker ps -a` : Pour lister tous les conteneurs[cite: 109, 153].
    * `sudo docker images` : Pour lister les images stockées[cite: 63, 158].
    * `sudo docker system prune` : Pour nettoyer le système[cite: 166].

### **Job 04 : Serveur Nginx Personnalisé**
* **Déploiement** : `sudo docker run -d -p 8080:80 nginx`[cite: 125].
* **Interaction** : Utilisation de `sudo docker exec -ti [ID] bash` pour entrer dans le conteneur[cite: 137].

## 🧠 Notions Apprises
* **Daemon** : Programme en arrière-plan qui gère les conteneurs[cite: 43, 44].
* **Image vs Conteneur** : L'image est le fichier exécutable, le conteneur est l'instance lancée[cite: 92, 93].
# Projet-derniere-chance-
