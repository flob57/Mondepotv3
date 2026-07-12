# DepotDash

Application React/Vite prête pour GitHub et Cloudflare Pages.

## Déploiement Cloudflare Pages

- Framework : Vite
- Commande de build : `npm run build`
- Dossier de sortie : `dist`
- Version Node recommandée : `22`

## Données

Cette première version stocke les données dans le navigateur (`localStorage`). Les liens Notion sont configurables dans Paramètres. La synchronisation API Notion nécessitera ensuite un Worker sécurisé et un jeton Notion ; les liens seuls ne donnent pas accès aux bases privées.
