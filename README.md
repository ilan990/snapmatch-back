# Application de Gestion de Photos avec Détection d'Images

Ce projet est une application web complète développée pour la gestion avancée de photos, utilisant React pour le frontend et Python avec Django pour le backend. L'application intègre la détection d'images basée sur l'intelligence artificielle pour organiser automatiquement les photos par personne détectée.

## Fonctionnalités

- **Téléchargement de Photos :** Permet aux utilisateurs de télécharger leurs photos dans l'application.
- **Gestion et Organisation :** Gérez et organisez vos photos téléchargées avec des descriptions et des tags.
- **Détection Automatique des Visages :** Utilisation de l'IA pour détecter les visages et organiser les photos par personne.
- **Interface Utilisateur Intuitive :** Interface moderne et conviviale grâce à l'utilisation de Tailwind CSS.
- **État Global Géré avec Redux :** Maintient un état global pour une gestion efficace des données.

## Backend (Python avec Django)

Le backend de l'application est développé en Python avec Django, utilisant une architecture robuste pour gérer les fonctionnalités essentielles telles que l'authentification, la gestion des utilisateurs, la gestion des photos, et la détection d'images basée sur l'IA.

### Technologies Utilisées

- Python
- Django
- PostgreSQL/MySQL (base de données)
- JWT (JSON Web Tokens) pour l'authentification
- Bibliothèques d'IA telles que OpenCV, dlib pour la détection d'images

### Installation et Exécution du Backend

1. Clonez ce repository :

   ```bash
   git clone https://github.com/ilan990/snapmatch-back.git
   cd snapmatch-back.git

2. Installez les dépendances Python nécessaires (de préférence dans un environnement virtuel) :
  
   ```bash
   pip install -r requirements.txt

3. Configurez la base de données PostgreSQL/MySQL en mettant à jour les paramètres de configuration dans settings.py.

4. Appliquez les migrations pour créer les tables de la base de données :

   ```bash
   python manage.py migrate

5. Démarrez le serveur Django :

   ```bash
   python manage.py runserver

Le backend sera accessible à l'adresse : http://localhost:8000.
