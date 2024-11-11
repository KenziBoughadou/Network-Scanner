# Projet : Scanner de Réseau ARP

## Description
Ce projet est un scanner de réseau basé sur le protocole ARP, conçu pour détecter les dispositifs actifs dans un réseau local. En utilisant des paquets ARP diffusés, l’outil identifie les adresses IP et MAC des appareils connectés dans un sous-réseau spécifié, fournissant une vue d’ensemble des dispositifs connectés.

## Objectifs et Fonctionnalités

- **Détection de Dispositifs sur le Réseau Local** : Envoie des paquets ARP en diffusion pour découvrir les appareils actifs dans un sous-réseau.
- **Collecte d'Adresses IP et MAC** : Récupère les adresses IP et MAC de chaque appareil détecté et les affiche sous forme de liste.
- **Interface CLI** : Utilisation d'arguments en ligne de commande pour spécifier la plage IP cible.

## Technologies Utilisées

- **Python** : Langage de programmation principal.
- **Scapy** : Bibliothèque pour la manipulation de paquets réseau et l’envoi de requêtes ARP.
- **Argparse** : Utilisé pour gérer les arguments en ligne de commande, permettant à l’utilisateur de spécifier une plage IP cible.

## Code et Structure

- **Fonction `get_arguments()`** : Gère les arguments en ligne de commande pour spécifier la plage IP cible.
- **Fonction `scan()`** : Crée et envoie des paquets ARP en diffusion pour récupérer les adresses IP et MAC des dispositifs sur le réseau.
- **Fonction `print_result()`** : Affiche les résultats de l'analyse, avec les adresses IP et MAC de chaque appareil détecté.

## Exemple d’Utilisation
En exécutant le script avec une plage IP cible, l’outil scanne le réseau, identifie les dispositifs actifs et affiche leurs adresses IP et MAC dans une table formatée.
