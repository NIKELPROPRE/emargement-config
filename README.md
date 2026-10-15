# emargement-config

Config distante lue au démarrage par les apps « Emargement Balzac » (poste et admin).

Pour changer l'adresse du serveur d'émargement sur tous les PC : modifier `webhookUrl`
dans `app-config.json` (URL en `https://` uniquement). `fallbackUrls` = adresses de secours
testées dans l'ordre. Les apps vérifient que l'adresse affiche bien la page d'émargement
avant de l'utiliser ; sinon elles passent à la suivante.
