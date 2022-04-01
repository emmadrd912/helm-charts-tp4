# Helm-charts-tp4

Créer un HELM Chart qui permet de déployer un service web et un service mariadb. 2 PV et 2PVC doivent être créer. Le serveur web aura accès à mariadb via la création d'un service.

De plus, mariadb et le serveur web pourront être configurés dynamiquement grâce aux variables définis dans  *values.yml*.

## Instalation

1. Cloner le repo.

2. Aller dans le dossier ``helm-charts-tp4/charts-tp4``, puis éxecuter la commande suivante pour installer le charts :

```
helm install -f values.yaml charts-tp4 .
```

> Les commandes pour se connecter au service seront décrite.

![](helm-tp4.jpg)
