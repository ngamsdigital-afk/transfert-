# NGAMS TRANSFER

Prototype web autonome en HTML, CSS et JavaScript, sans dépendance externe.

## Tester en local

Depuis le dossier du projet, démarrez un serveur statique :

```sh
python3 -m http.server 8000
```

Ouvrez ensuite <http://localhost:8000> dans un navigateur. Vérifiez le tableau de bord, le simulateur, le code de parrainage et l’historique ; les simulations restent dans le stockage local du navigateur et survivent à un rechargement. Le bouton **Effacer** supprime cet historique.

## Ajouter à l’écran d’accueil iPhone

Publiez les fichiers du projet sur une adresse HTTPS, ouvrez-la dans Safari sur iPhone, puis choisissez **Partager → Sur l’écran d’accueil**. L’application utilise le manifeste web, les métadonnées iOS et une icône dédiée.

## Mode démonstration

Aucun transfert ni paiement réel n’est effectué. Aucune donnée bancaire n’est demandée ou collectée. Les frais affichés sont fictifs et aucun taux de change réel n’est utilisé.
