# Ansible Role: Webapp

Ce rôle Ansible configure une application web avec Nginx.

## Prérequis

- Ansible >= 2.9
- Accès à un serveur configuré

## Variables

Voici les variables disponibles avec leurs valeurs par défaut :

```yaml
webapp_port: 8080        # Port pour l'application web
webapp_server_name: ""   # Nom du serveur
