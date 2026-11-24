Objectifs

- Manipuler des conteneurs en mode interactif (run, exec, logs, stop, rm) ;
- Construire une image à partir d'un Dockerfile ;
- Conserver des données avec les volumes (volumes nommés et bind mounts) ;
- Faire communiquer des conteneurs grâce aux réseaux Docker ;
- Décrire et lancer une application multi-services avec Docker Compose.

Organisation du dossier

tp-docker/
├── TP_Docker.md ← cet énoncé
├── ex1/app/hello.py ← programme interactif (exercice 1)
├── ex2/site/index.html ← site statique (exercice 2)
├── ex3/web/index.html ← page servie par nginx (exercice 3)
├── ex4/app/ ← application Flask + Redis (exercice 4)
└── ex5/ ← projet de synthèse (exercice 5)
├── app/ ← API Flask + PostgreSQL
├── db/init.sql
├── proxy/nginx.conf
└── .env.example
