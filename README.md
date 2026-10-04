# Lien de partage de Collectionception

Ce dépôt ne contient qu'une page : celle qui s'ouvre quand on touche un lien de partage envoyé depuis l'application Android Collectionception.

Elle est en ligne à l'adresse <https://lsa2222.github.io/collectionception-lien/>.

## Ce qu'elle fait

Une messagerie n'affiche comme un lien qu'une adresse web. L'application envoie donc `https://lsa2222.github.io/collectionception-lien/#<code>`, et la page renvoie vers l'application :

- sur un téléphone Android où Collectionception est installée, l'application s'ouvre sur la collection partagée ;
- ailleurs, la page affiche le code à coller dans l'application : onglet Profil, puis « Ouvrir un lien de partage ».

## Ce qu'elle ne fait pas

Elle ne montre pas la collection, ne charge rien d'extérieur et n'envoie rien. Le code suit le `#` de l'adresse, que les navigateurs ne transmettent pas au serveur : il ne quitte pas l'appareil.
