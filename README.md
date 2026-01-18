# Système de Gestion d'emprunts de livres

Une application web moderne et robuste permettant de gérer les flux d'emprunts, les stocks de livres et les membres d'une bibliothèque.

---

##  Thème : "Émeraude & Glassmorphism"
Le projet adopte une identité visuelle unique :
- **Couleurs** : Dégradés de vert forêt et vert émeraude (`#1b4332` vers `#2d6a4f`).
- **Style** : Utilisation du **Glassmorphism** (cartes translucides avec effet de flou en arrière-plan).
- **Interface** : Épurée, moderne et intuitive, mettant l'accent sur la lisibilité des statistiques.

---

##  Description
Cette application facilite le travail des bibliothécaires en automatisant les tâches répétitives. Elle permet une gestion centralisée des livres et des étudiants, tout en offrant un suivi précis des emprunts en cours. Le système sépare distinctement les privilèges entre l'administrateur (gestion totale) et l'étudiant (consultation).

---

##  Installation

### 1. Prérequis
- Serveur local : **XAMPP**.
- PHP version **8.0** .
- Navigateur web moderne (Edge).

### 2. Procédure
1. **Cloner le projet** : Placez les fichiers dans votre dossier `htdocs` ou `www`.
2. **Base de données** : 
   - Créez une base de données nommée `biblio` via PHPMyAdmin.
   - Importez le fichier `biblio.sql` situé à la racine du projet.
3. **Configuration** : 
   - Ouvrez le fichier `config/db.php`.
   - Modifiez les identifiants de connexion si nécessaire (hôte, utilisateur, mot de passe).

---

##  Structure du Projet
Le dépôt est organisé de manière modulaire :
- `config/` : Contient la connexion PDO à la base de données.
- `includes/` : Regroupe les composants réutilisables (`header.php`, `footer.php`).
- `js/` : Fichiers JavaScript pour les notifications et les animations.
- `uploads/` : Répertoire de stockage des couvertures de livres.
- `index.php` : Tableau de bord principal de l'administrateur.
- `auth.php` : Logique de sécurité et de restriction des accès.

---

##  Utilisation

### Accès Administrateur
- **Dashboard** : Visualisation des statistiques clés dès la connexion.
- **Emprunts** : Enregistrement rapide via des sélecteurs dynamiques (Étudiants/Livres).
- **Retours** : Bouton d'action direct pour marquer un livre comme "Rendu".

### Accès Étudiant
- **Espace Personnel** : L'étudiant peut voir la liste de ses livres empruntés et leurs dates.

---

##  Technologies
- **Backend** : PHP 8 (Architecture procédurale propre avec PDO).
- **Frontend** : HTML5, CSS3 (Flexbox/Grid), Bootstrap 5.
- **Base de données** : MySQL.
- **Bibliothèques JS** : 
  - **SweetAlert2** : Pour les fenêtres de confirmation et alertes d'erreurs.
  - **FontAwesome** : Pour les icônes vectorielles.

---

##  Auteurs
- **[Davila]** - *Conception, Développement, design et test*
- **[Fresnel]** - *Conception, Développpement*


---
