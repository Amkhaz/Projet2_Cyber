# Projet partage des fichiers : Répartition des tâches

## Membre 1: Authentification et Gestion de Profil

### Vues

- Créer les pages `index.php`, `register.php`, `login.php` et `profile.php` avec les formulaires nécessaires.

### Contrôleurs

- Créer le fichier `register_process.php` pour traiter les données du formulaire d'inscription.
- Créer le fichier `login_process.php` pour traiter les données du formulaire de connexion.
- Créer le fichier `profile_data.php` pour gérer les données de profil.

### Modèles

- Créer un modèle `UserModel.php` pour gérer les requêtes liées à l'utilisateur dans la base de données.

---

## Membre 2: Upload, Téléchargement et Partage de Fichiers

### Vues

- Créer les pages `upload.php`, `download.php` et `share.php` avec les formulaires nécessaires.

### Contrôleurs

- Créer le fichier `upload_process.php` pour gérer l'upload des fichiers.
- Créer le fichier `download_process.php` pour gérer le téléchargement.
- Créer le fichier `share_process.php` pour gérer le partage de fichiers.

### Modèles

- Créer un modèle `FileModel.php` pour gérer les requêtes liées aux fichiers dans la base de données.

---

## Membre 3: Gestion des Fichiers et Audit de Sécurité

### Vues

- Créer les pages `file_management.php`, `audit.php` et `error.php`.

### Contrôleurs

- Créer le fichier `file_management_process.php` pour gérer les actions sur les fichiers.
- Créer le fichier `audit_process.php` pour l'audit de sécurité.

### Modèles

- Créer un modèle `FileManagementModel.php` pour gérer la suppression et le renommage de fichiers.
- Créer un modèle `AuditModel.php` pour gérer les audits de sécurité.
