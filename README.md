# superMoxxie — Téléchargements Windows

Assistant personnel avec Chat, École et Université. Le même chat peut utiliser Ollama local ou un abonnement ChatGPT autorisé, avec la personnalité de Moxxie et un historique local.

**[Télécharger superMoxxie pour Windows](https://github.com/AlvaroCatoiraP/Moxxie-downloads/releases/latest/download/Moxxie-Setup.exe)**

Windows 10/11 64 bits. Python est inclus. Le nom technique Moxxie-Setup.exe et le dossier Moxxie sont conservés pour mettre à jour les installations existantes.

## Démarrer

Installer puis ouvrir Moxxie : la fenêtre affiche superMoxxie. Pour le mode local, préparer Ollama depuis Réglages. Pour l’abonnement ChatGPT, ouvrir **Compte ChatGPT → Continue with ChatGPT**, se connecter dans le navigateur et choisir un modèle disponible.

L’accès dépend du compte, du forfait et de l’autorisation accordée à cette application. Il n’est pas garanti pour tous les comptes ou applications privées ; la connexion réelle reste à vérifier par l’utilisateur.

Un aperçu précède chaque envoi connecté : message, contexte récent, personnalité et souvenirs utiles sont transmis à OpenAI. Aucun livre n’est recherché automatiquement dans ce mode. Aucune API payante de secours n’est utilisée. La connexion ne donne pas accès aux conversations ou à la mémoire du site ChatGPT. Les conditions de traitement côté service doivent être vérifiées pour la voie d’accès et le compte concernés ; store=false ne garantit pas une conservation nulle.

Le contexte courant est conservé au changement de moteur. **Historique → Reprendre les échanges récents dans le chat** recharge les derniers échanges. La mémoire exploite les messages de l’utilisateur ; les réponses du modèle ne deviennent pas automatiquement des connaissances validées et ne réentraînent pas Ollama.

Université conserve son correcteur avec clé API distincte et facturation API possible, uniquement sur demande. Ce correcteur ne sert pas de moteur de secours au chat.

## Mettre à jour

Ouvrir **Vérifier les mises à jour → Faire la mise à jour** : téléchargement, vérification SHA-256, sauvegarde du profil, fermeture, installation silencieuse et relancement. Fermer les autres fenêtres Moxxie. Un téléchargement invalide bloque l’installation. Une panne pendant l’installation ne dispose pas encore d’un retour automatique à la version précédente.

Les anciennes versions demandent encore de lancer une première fois l’installateur téléchargé. Une fois 0.5.0 installée, les mises à jour suivantes pourront utiliser le nouveau bouton.

Les livres, souvenirs et résultats restent dans `%LOCALAPPDATA%\Moxxie\data`, séparément du programme. **Sauvegardes et restauration** crée une archive du profil et des documents originaux disponibles. Garder également une sauvegarde sur un autre support.

## À savoir

- Aucun livre personnel ni cours tiers n’est distribué.
- Les identifiants ChatGPT sont protégés par Windows dans un dossier séparé ; ne jamais partager ce dossier.
- La mémoire documentaire ne constitue pas un entraînement du modèle ni une certification d’expertise.
- L’installateur n’est pas signé ; Windows peut afficher un avertissement de réputation.
- Télécharger uniquement depuis les Releases de ce dépôt. Chaque installateur est accompagné de SHA256SUMS.txt.

Ce dépôt contient les téléchargements publics et leur documentation. Le code de développement reste privé.
