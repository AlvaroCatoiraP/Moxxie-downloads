# superMoxxie — Téléchargements Windows

Version **0.7.0** : assistant personnel avec quatre espaces, **Chat**, **Bibliothèque**, **École** et **Université**, et compagnon animé.

**[Télécharger pour Windows](https://github.com/AlvaroCatoiraP/Moxxie-downloads/releases/latest/download/Moxxie-Setup.exe)** · **[Manuel HTML complet](https://github.com/AlvaroCatoiraP/Moxxie-downloads/releases/latest/download/Moxxie-Documentation.html)**

Windows 10/11 64 bits ; Python inclus. Installer ou mettre à jour au même emplacement conserve le profil, les souvenirs et les livres dans `%LOCALAPPDATA%\Moxxie\data`. Une sauvegarde externe reste recommandée.

## Nouveautés

- Ajout manuel de souvenirs, dont un souvenir par ligne, avec contrôle des doublons.
- Discussions séparées, historique consultable, brouillons automatiques et saisie pendant une réponse.
- Modification de la dernière question et relance dans une nouvelle discussion.
- Sources cliquables et conservation des références avec la discussion.
- Recherche globale dans les discussions, souvenirs, livres et leçons.
- Import multiple de documents, dépôt de fichiers Windows et bilan par fichier.
- Fiches et quiz locaux depuis les livres, révisions espacées selon les erreurs.
- Corrections proposées, puis réutilisées seulement après validation explicite.
- Export des discussions en PDF et texte.
- Panneaux chargés à la demande, taille du texte et contraste réglables, raccourcis clavier.
- Sauvegardes programmables pendant l’ouverture ; menu du compagnon enrichi.
- Dictée et lecture Windows, ou service vocal en ligne choisi explicitement avec clé API distincte.
- Proposition automatique des nouvelles versions, installation choisie ou rappel le lendemain.
- Manuel HTML autonome : 27 chapitres, plus de 11 000 mots, recherche, thème et impression.

Windows 10/11 64 bits. Les livres et le profil restent séparés du programme. Une sauvegarde précède la migration du profil. Quitter les autres instances avant installation.

Validation : 261 tests automatisés réussis et contrôle de l’interface sur un profil temporaire. Les appels vocaux distants sont simulés : le fonctionnement réel dépend des composants Windows, du microphone et du compte API. Aucun livre personnel ni identifiant n’est distribué.

Télécharger Moxxie-Setup.exe pour installer ou mettre à jour, et Moxxie-Documentation.html pour consulter le manuel sans installation. SHA256SUMS.txt contient les empreintes des deux fichiers.

## Utiliser Moxxie

Le chat peut utiliser Ollama ou un serveur local compatible. Les connexions à des services externes dépendent de leurs droits et comptes. Les fonctions de voix en ligne et le correcteur d’Université nécessitent une clé API distincte et peuvent être facturés par le service ; aucun appel vocal n’est envoyé sans choix explicite.

Dans la version 0.7.0, les nouvelles versions sont proposées automatiquement. Choisir **Installer maintenant** ou reporter de 24 heures. Les versions précédentes peuvent ouvrir **Réglages → Application → Vérifier les mises à jour**, ou télécharger l’installateur ci-dessus. La mise à jour vérifie l’empreinte SHA-256, sauvegarde, installe puis relance. Un retour automatique après panne d’installation n’est pas encore disponible.

Le manuel HTML fonctionne hors ligne, avec recherche et impression. Il est aussi accessible dans **Outils → Documentation détaillée** et par **F1**.

Aucun profil ni livre personnel n’est publié. Le code de développement reste dans un dépôt privé. L’installateur n’est pas signé ; Windows peut afficher un avertissement de réputation.
