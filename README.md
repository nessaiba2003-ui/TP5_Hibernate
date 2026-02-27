TP 5 : Requêtes pour "salles disponibles par créneau", recherche multi-critères, pagination d'un listing

## Objectifs du TP

Ce travail pratique vous permet de maîtriser des fonctionnalités essentielles pour une application de réservation de salles :

1. **Implémenter une requête pour trouver les salles disponibles par créneau horaire**
   - Gérer les conflits de réservation
   - Vérifier la disponibilité des salles sur des plages horaires spécifiques

2. **Créer une recherche multi-critères pour les salles**
   - Utiliser l'API Criteria de JPA
   - Combiner plusieurs filtres de recherche (capacité, équipements, localisation, etc.)

3. **Mettre en place un système de pagination pour les listings**
   - Optimiser les performances avec de grands volumes de données
   - Permettre une navigation fluide dans les résultats

## Étapes de réalisation

 Configuration de Hibernate et H2
- Configuration de la persistance
- Mise en place de la base de données H2 en mémoire

 Création des entités de base
- Modélisation des entités métier (Salle, Réservation, etc.)
- Définition des relations entre entités

 Création du Repository pour les requêtes avancées
- Implémentation des méthodes de recherche personnalisées
- Utilisation de JPQL et Criteria API

Création d'un service pour encapsuler la logique métier
- Séparation des couches métier et d'accès aux données
- Implémentation des règles de gestion

 Création d'une classe utilitaire pour la pagination
- Gestion de la pagination des résultats
- Paramétrage de la taille des pages

 Création d'une classe principale pour tester les fonctionnalités
- Tests unitaires des différentes fonctionnalités
- Validation des requêtes et de la pagination

 Exécution du projet
- Lancement et validation du fonctionnement



##  Technologies utilisées

- **Hibernate** : ORM pour la persistance Java
- **JPA** : Java Persistence API
- **H2** : Base de données en mémoire pour le développement
- **Criteria API** : Pour les requêtes dynamiques multi-critères

  ##  Compétences développées
 Maîtrise des requêtes JPQL avancées
 Utilisation de l'API Criteria pour des recherches complexes
 Implémentation de la pagination efficace
 Architecture en couches (Repository, Service)
 Gestion des contraintes temporelles dans les bases de données
 ##   Conclusion
Ce TP vous a permis de développer des fonctionnalités essentielles pour créer une application de réservation de salles conviviale et performante, permettant aux utilisateurs de trouver rapidement les salles qui répondent à leurs besoins.

  <img width="1600" height="860" alt="Capture d’écran 2026-02-25 213251" src="https://github.com/user-attachments/assets/d6f0b6b7-3237-48e3-94e3-bbdeea7cb25f" />
<img width="1600" height="860" alt="Capture d’écran 2026-02-25 213336" src="https://github.com/user-attachments/assets/13f47d07-7890-4421-b65f-721977b5cb8a" />
<img width="1600" height="860" alt="Capture d’écran 2026-02-25 213336" src="https://github.com/user-attachments/assets/54bc8633-45ff-4eb9-a643-e881ef758a63" />
<img width="1600" height="860" alt="Capture d’écran 2026-02-25 213426" src="https://github.com/user-attachments/assets/835bc502-d161-4986-b455-7d93c555e00d" />
<img width="1600" height="860" alt="Capture d’écran 2026-02-25 213449" src="https://github.com/user-attachments/assets/dd0af67b-12a4-4a62-b296-379983689296" />
<img width="1600" height="860" alt="Capture d’écran 2026-02-25 213513" src="https://github.com/user-attachments/assets/48c3f883-9123-4081-88dc-3f6598eb76ab" />
<img width="1600" height="860" alt="Capture d’écran 2026-02-25 213545" src="https://github.com/user-attachments/assets/3dc97390-6cd2-4e40-839f-2197f6f39466" />
<img width="1600" height="860" alt="Capture d’écran 2026-02-25 213610" src="https://github.com/user-attachments/assets/e35cd235-9b23-49d3-9673-d415f7688653" />

<img width="1600" height="860" alt="Capture d’écran 2026-02-25 213635" src="https://github.com/user-attachments/assets/ce954938-5240-4f49-9ea8-bf0d13ecc26f" />

<img width="1600" height="860" alt="Capture d’écran 2026-02-25 213656" src="https://github.com/user-attachments/assets/0aef2ce4-f0cc-49ba-9f30-d7d7f9c23727" />

<img width="1600" height="860" alt="Capture d’écran 2026-02-25 213718" src="https://github.com/user-attachments/assets/d5d9f919-7bb9-4a5a-9ca3-f62962be2670" />

<img width="1600" height="860" alt="Capture d’écran 2026-02-25 214044" src="https://github.com/user-attachments/assets/4e8aee6a-3a46-4c7c-a74c-832ddc255b90" />

<img width="1600" height="860" alt="Capture d’écran 2026-02-25 214104" src="https://github.com/user-attachments/assets/4db22f8d-b17d-4134-8ef7-2359c262f2e0" />

<img width="1600" height="860" alt="Capture d’écran 2026-02-25 214128" src="https://github.com/user-attachments/assets/74d98e21-af4b-4844-802f-9ebb2247e41b" />

<img width="1600" height="860" alt="Capture d’écran 2026-02-25 214149" src="https://github.com/user-attachments/assets/16bfa055-229a-4cac-9c81-e0911a640408" />

<img width="1600" height="860" alt="Capture d’écran 2026-02-25 214212" src="https://github.com/user-attachments/assets/da254dd5-979e-4621-b2bd-ab27a1fefa86" />

<img width="1600" height="860" alt="Capture d’écran 2026-02-25 214235" src="https://github.com/user-attachments/assets/55417f7b-fbda-4359-a614-6c8a8da1a0ad" />

