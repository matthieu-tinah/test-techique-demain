🔔 Notifications en Temps Réel – Architecture Next.js (App Router)

Un système complet de notification en temps réel, déclenché automatiquement lorsqu’un produit passe en rupture de stock.

🚀 Stack Technique
🧩 Frontend

Next.js 14 (App Router)

React Server Components

Next api (recommendé) ou server actions ,

Architecture orientée modules

Modules :

modules/product

modules/notification

modules/user

🛠 Backend

Next.js API Routes ou tRPC

🗄 Base de données

Prisma ORM

PostgreSQL

⚡ Temps réel

Socket.io (canaux de notifications en direct)


🔄 Fonctionnement du Système

Un produit passe en rupture de stock

Le module Product déclenche un événement

Le module Notification diffuse l’alerte via Socket.io

Le frontend écoute et affiche :

🔴 Alerte visuelle

🔔 Badge de notification

📩 Liste des notifications

📦 Livrables
🎥 Capture vidéo

Une démonstration complète du système de notifications en temps réel :

👉 [Insérer ici le lien vers la vidéo de démonstration]

🔗 Lien GitHub

Le code source du projet est disponible ici :

👉 Lien GitHub du projet
