# voipass-assets

Images servies publiquement pour VOIPass.

Google Chat n'affiche pas les émojis personnalisés dans les messages postés par
un webhook : ils exigent une authentification utilisateur. VOIPass envoie donc
l'image de l'émoji, et Google la charge par son proxy — d'où la nécessité d'une
URL publique, que le serveur VOIPass (interne) ne peut pas fournir.

| Fichier | Usage |
|---|---|
| `shprime.png` | Émoji posté dans l'espace d'équipe à chaque passage ajouté au SH Counter (`SH_COUNTER_CHAT_EMOJI_URL`) |
