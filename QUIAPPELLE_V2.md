# QuiAppelle 0.2

Application Android privée pour identifier les appels inconnus sans remplacer Google Téléphone.

Fonctions principales :
- laisse immédiatement sonner l’appel dans Google Téléphone ;
- recherche les variantes publiques du numéro avec l’API Brave Search ;
- classe le résultat : identifié, présent sur Internet, publicité/spam probable ou inconnu ;
- envoie une notification avec une action de création de contact ;
- chiffre la clé Brave avec Android Keystore ;
- n’envoie pas le carnet d’adresses vers un serveur.

Le fichier APK est construit par GitHub Actions après vérification SHA-256 de l’archive source.
