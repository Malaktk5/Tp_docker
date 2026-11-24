Objectifs
• Manipuler des conteneurs en mode interactif (run, exec, logs, stop, rm) ;
• Construire une image à partir d'un Dockerfile ;
• Conserver des données avec les volumes (volumes nommés et bind mounts) ;
• Faire communiquer des conteneurs grâce aux réseaux Docker ;
• Décrire et lancer une application multi-services avec Docker Compose.
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
Conventions
• Toutes les commandes sont à lancer depuis la racine du TP (le dossier tp-
docker/), sauf indication contraire.
• $(pwd) désigne le dossier courant. Sous PowerShell, utilisez ${PWD} ; sous Windows,
un terminal WSL2 est recommandé.
• Les questions sont numérotées Q1, Q2… : répondez-y dans votre compte rendu.
• Nettoyez à la fin de chaque exercice (commandes données) : les exercices réutilisent
les mêmes noms et les mêmes ports (8080, 8081, 8082, 5000).
