# Moxxie — Téléchargements Windows

Assistant personnel local avec trois espaces : **Chat**, **École** et **Université**.

## Télécharger

**[Télécharger Moxxie-Setup.exe](https://github.com/AlvaroCatoiraP/Moxxie-downloads/releases/latest/download/Moxxie-Setup.exe)**

Windows 10/11 64 bits. Python est inclus : aucune installation de Python n’est nécessaire.

## Premier lancement

1. Exécuter l’installateur et ouvrir Moxxie depuis son raccourci.
2. Suivre le guide de bienvenue. Installer Ollama depuis le bouton officiel si nécessaire.
3. Cliquer **Préparer le modèle local**. Internet est nécessaire pour télécharger le modèle la première fois.
4. Discuter dans Chat ou importer ses propres PDF dans École.

Université utilise une clé API OpenAI configurée par l’utilisateur. Les appels externes sont déclenchés explicitement et peuvent être facturés à son compte API.

## Mises à jour et livres existants

Cliquer **Vérifier les mises à jour** dans Moxxie. Lorsqu’une version plus récente existe, l’application propose le téléchargement officiel dans le navigateur. Fermer Moxxie avant d’exécuter l’installateur.

Les livres indexés, fiches, souvenirs et résultats sont conservés dans `%LOCALAPPDATA%\Moxxie\data`, séparément du programme. Les mises à jour et la désinstallation ne suppriment pas ce dossier. **Sauvegardes et restauration** crée une archive complète avec les originaux conservés et l’avatar. Une copie quotidienne est créée à l’ouverture. Garder aussi une copie sur un autre support et surveiller l’espace disque : aucune archive n’est supprimée automatiquement.

La restauration présente le contenu et sauvegarde l’état courant avant remplacement ; elle accepte aussi les anciennes bases `.db`/`.sqlite`. Une base seule ne contient pas les PDF. Les nouveaux imports conservent leurs originaux ; réimporter le même fichier le rattache sans doublon.

La version 0.4.0 ajoute une bibliothèque filtrable, les sources du dernier échange et la progression par thème. La recherche par sens nécessite un modèle local déjà installé et une indexation explicite. L’OCR nécessite Poppler et Tesseract, installés séparément. L’avatar se choisit dans les outils locaux des réglages.

Si vous utilisiez une ancienne version en dossier, ouvrez **Réglages → Récupérer une ancienne installation** sur une nouvelle installation vide et choisissez son fichier `data\memory\moxxie.db`. L’ancienne base est copiée et reste intacte. Une bibliothèque existante ne peut pas être écrasée par cet import. Les PDF originaux restent à leur emplacement.

## À savoir

- Cette distribution ne contient pas de livres personnels ni de cours tiers : importez vos propres documents.
- L’apprentissage enrichit des connaissances documentaires ; il ne modifie pas les paramètres du modèle et ne certifie pas une expertise.
- L’installateur initial n’est pas signé avec un certificat de signature de code ; Windows peut afficher un avertissement de réputation.
- Téléchargez uniquement depuis les Releases de ce dépôt. Une empreinte SHA-256 accompagne chaque installateur.

Ce dépôt contient les téléchargements publics. Le dépôt de développement est privé.
