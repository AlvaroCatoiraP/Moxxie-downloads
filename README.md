# superMoxxie — Téléchargements Windows

La version **0.6.5** ajoute le choix **Serveur local avancé** dans le chat. Il connecte Moxxie à un moteur local comme vLLM ou SGLang, avec des exemples MiMo, GLM et Kimi. Le moteur et les poids du modèle doivent être installés séparément ; aucun grand modèle n’est téléchargé automatiquement. La mémoire personnelle, les onglets sombres, les quatre espaces et le compagnon sont conservés.

Assistant personnel avec quatre espaces : **Chat**, **Bibliothèque**, **École** et **Université**. Le même chat peut utiliser Ollama, un serveur local avancé ou un abonnement ChatGPT autorisé, avec la personnalité de Moxxie et un historique local.

**[Télécharger superMoxxie pour Windows](https://github.com/AlvaroCatoiraP/Moxxie-downloads/releases/latest/download/Moxxie-Setup.exe)**

Windows 10/11 64 bits. Python est inclus. Le nom technique Moxxie-Setup.exe et le dossier Moxxie sont conservés pour mettre à jour les installations existantes.

## Démarrer

La version **0.6.0** réorganise l’interface : bibliothèque intégrée, prochaine étape proposée dans École, questions et corrections séparées dans Université. Les réglages sont regroupés dans **Apparence**, **Connexions**, **Données** et **Application**.

Un compagnon animé reste au bord droit de l’écran. **Réglages → Apparence** permet de modifier sa taille, sa visibilité et la pause. La croix masque la fenêtre quand le compagnon est actif ; son menu de clic droit ou **Réglages → Application** permet de quitter complètement.

Installer puis ouvrir Moxxie : la fenêtre affiche superMoxxie. Pour le mode local, préparer Ollama depuis Réglages. Pour l’abonnement ChatGPT, ouvrir **Compte ChatGPT → Continue with ChatGPT**, se connecter dans le navigateur et choisir un modèle disponible.

L’accès dépend du compte, du forfait et de l’autorisation accordée à cette application. Il n’est pas garanti pour tous les comptes ou applications privées ; la connexion réelle reste à vérifier par l’utilisateur.

Un aperçu précède chaque envoi connecté : message, contexte récent, personnalité et souvenirs utiles sont transmis à OpenAI. Les sources locales peuvent être fournies en mode documentaire. Les demandes explicites de mémorisation et les rappels simples du prénom sont traités localement, sans envoi au modèle. Aucune API payante de secours n’est utilisée. La connexion ne donne pas accès aux conversations ou à la mémoire du site ChatGPT. Les conditions de traitement côté service doivent être vérifiées pour la voie d’accès et le compte concernés ; store=false ne garantit pas une conservation nulle.

Le contexte courant est conservé au changement de moteur. **Historique → Reprendre les échanges récents dans le chat** recharge les derniers échanges. La mémoire exploite les messages de l’utilisateur ; les réponses du modèle ne deviennent pas automatiquement des connaissances validées et ne réentraînent pas Ollama.

Université conserve son correcteur avec clé API distincte et facturation API possible, uniquement sur demande. Ce correcteur ne sert pas de moteur de secours au chat.

## Mettre à jour

Dans la version 0.6.0, ouvrir **Réglages → Application → Vérifier les mises à jour**, puis **Faire la mise à jour**. Dans la version 0.5.0, le bouton reste dans le menu de gauche. La mise à jour effectue le téléchargement, la vérification SHA-256, la sauvegarde du profil, la fermeture, l’installation silencieuse et le relancement. Quitter complètement les autres fenêtres Moxxie avant de continuer. Un téléchargement invalide bloque l’installation. Une panne pendant l’installation ne dispose pas encore d’un retour automatique à la version précédente.

Les anciennes versions demandent encore de lancer une première fois l’installateur téléchargé. Une fois 0.5.0 installée, les mises à jour suivantes pourront utiliser le nouveau bouton.

Les livres, souvenirs et résultats restent dans `%LOCALAPPDATA%\Moxxie\data`, séparément du programme. **Sauvegardes et restauration** crée une archive du profil et des documents originaux disponibles. Garder également une sauvegarde sur un autre support.

## À savoir

- Aucun livre personnel ni cours tiers n’est distribué.
- Les identifiants ChatGPT sont protégés par Windows dans un dossier séparé ; ne jamais partager ce dossier.
- La mémoire documentaire ne constitue pas un entraînement du modèle ni une certification d’expertise.
- L’installateur n’est pas signé ; Windows peut afficher un avertissement de réputation.
- Télécharger uniquement depuis les Releases de ce dépôt. Chaque installateur est accompagné de SHA256SUMS.txt.

Ce dépôt contient les téléchargements publics et leur documentation. Le code de développement reste privé.

## Serveur local avancé

Choisir **Serveur local avancé** dans le chat, ou ouvrir **Réglages → Connexions → Options avancées**. Renseigner l’adresse locale (par exemple `http://127.0.0.1:8000/v1`), tester la liste des modèles puis sélectionner le modèle réellement chargé et enregistrer. Les noms proposés sont des exemples, pas des modèles inclus dans l’installateur.

Le serveur doit exécuter les poids sur votre propre matériel. Le chat utilise uniquement une adresse de boucle locale, sans basculement automatique vers une API en ligne. Désactiver Wikipédia pour ne pas lancer de recherches en ligne facultatives. École et l’élève d’Université conservent leur moteur Ollama existant.
