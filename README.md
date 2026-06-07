Le système crée automatiquement un tunnel Cloudflare et récupère l’URL générée. Dès que cette URL change, le serveur met à jour le fichier Gist avec la nouvelle adresse.
Cela permet d’avoir toujours un lien valide pour accéder à BirdNET‑Go, même si le tunnel se recrée ou redémarre.Grâce à cette mise à jour automatique du Gist, BirdNET‑Go peut fonctionner sans interruption, sans avoir besoin de modifier les fichiers à la main.

Pour suivre ce qui se passe, deux topics ntfy sont utilisés :

[timeo‑tunnel](https://ntfy.sh/timeo-tunnel) : il indique si le tunnel Cloudflare est actif, en pause ou en erreur. Cela permet de savoir rapidement si le lien est prêt ou non.

[Bird](https://ntfy.sh/Bird) : il envoie des notifications liées à BirdNET‑Go, par exemple quand une identification est faite ou quand une action importante se produit.

Ces notifications permettent de surveiller le serveur sans avoir besoin de se connecter dessus. Tout est automatique : le serveur récupère l’URL, vérifie le tunnel, corrige les problèmes et envoie les informations nécessaire

Accéder au portail :  https://timeobonnin-prog.github.io


<img width="1915" height="957" alt="image" src="https://github.com/user-attachments/assets/354d6a74-5037-4816-b2f8-df1dd1135ab2" />


<img width="1920" height="956" alt="image" src="https://github.com/user-attachments/assets/ade537d1-a532-4ae7-8029-6040b6e92d16" />



VoLe projet est ouvert à tous. Vous pouvez contribuer au dépôt GitHub en proposant des améliorations, des corrections ou de nouvelles idées. Pour cela, il suffit de créer une pull request dans le dépôt :[ici](https://github.com/timeobonnin-prog/timeobonnin-prog.github.io/pulls)





Un grand merci à tous les contributeurs pour leur aide, leurs retours et leur bienveillance. Le projet continue d’évoluer grâce à eux.
