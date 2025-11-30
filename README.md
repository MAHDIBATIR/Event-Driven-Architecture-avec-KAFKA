# Event Driven Architecture avec KAFKA

Projet de démonstration d'une architecture événementielle utilisant Apache Kafka et Spring Cloud Streams.

## Vidéo de référence
https://www.youtube.com/watch?v=8uY7JE_X_Fw&authuser=0

## Étapes du projet

### Étape 1: Installation et configuration manuelle de Kafka
- Téléchargement de Kafka
- Démarrage de Zookeeper
- Démarrage de Kafka-server
- Tests avec kafka-console-producer et kafka-console-consumer

### Étape 2: Installation avec Docker
- Création du fichier docker-compose.yml
- Démarrage des conteneurs Docker (Zookeeper et Kafka-broker)
- Tests avec kafka-console-producer et kafka-console-consumer

### Étape 3: Application Spring Cloud Streams
- Service Producer KAFKA via REST Controller
- Service Consumer KAFKA
- Service Supplier KAFKA
- Service de Data Analytics Real Time avec Kafka Streams
- Application Web pour affichage en temps réel

## Prérequis

- Java 21
- Maven 3.x
- Docker et Docker Compose
- Git

## Technologies utilisées

- Spring Boot 3.5.6
- Spring Cloud Streams 2025.0.0
- Apache Kafka
- Kafka Streams
- Lombok
