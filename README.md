# plextraktsync
conf Portainer / dockercompose

## Configuration

1. Créer une stack dans Portainer et y coller le contenu du fichier [`docker-compose.yml`](docker-compose.yml).
2. Modifier les deux containers `plextraktsync` et `plextraktsyncwatch` en activant la console en **Interactive & TTY** `(-i -t)`.
3. Lancer la console dans chaque containers en mode `Use custom command` avec comme commande `plextraktsync`.
4. Suivez les questions du configurateur. Pour créer ou récupérer une configuration Trakt aller à https://trakt.tv/oauth/applications
5. Finalisez
6. Dans le container `plextraktsyncwatch` forcer la command à `watch`.
