NOIR DISTRICT — BOUTIQUE STREETWEAR (prototype frontend)
========================================================

CONTENU
- index.html : structure du site
- style.css  : design responsive noir/blanc avec accent vert
- script.js  : catalogue exemple, filtres, recherche, tailles/couleurs, panier local et commande WhatsApp

LANCEMENT LOCAL
1. Décompressez le ZIP.
2. Ouvrez index.html dans Chrome.
   Pour un aperçu plus fiable, utilisez VS Code + l'extension Live Server.

AVANT DE RECEVOIR DES COMMANDES
1. Ouvrez script.js.
2. Remplacez WHATSAPP_NUMBER = "213000000000" par votre numéro WhatsApp au format international sans +, espace ni tiret.
   Exemple de format : 213XXXXXXXXX (remplacez X par votre numéro).
3. Remplacez les noms, prix, couleurs et tailles d'exemple dans PRODUCTS par vos vrais produits.
4. Testez une commande sur votre propre téléphone.

IMPORTANT
- Les produits et prix sont fictifs, à confirmer et à remplacer.
- Le panier est stocké dans le navigateur du client (localStorage).
- Ce ZIP n'inclut PAS de vraie base de données, de tableau de bord administrateur, de gestion de stock multi-appareil, ni de paiement en ligne. Les commandes sont envoyées par WhatsApp.
- GitHub Pages peut héberger gratuitement cette version statique. Il ne fournit pas de backend/DB.
- Pour un vrai back-office et une base de données, il faudra ajouter un backend (par ex. PHP/MySQL ou Supabase/Firebase) et sécuriser les accès administrateur.
