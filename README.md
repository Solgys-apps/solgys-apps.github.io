# Solgys Apps — site public

Site GitHub Pages de Solgys Apps : la page d’accueil et les pages publiques de **Jauge**, l’application iPhone de comparaison des prix des carburants et des bornes de recharge.

## Pages de Jauge

- Assistance : <https://solgys-apps.github.io/lajauge/support/>
- Politique de confidentialité : <https://solgys-apps.github.io/lajauge/privacy/>
- E-mail : `solgys.apps@gmail.com`, avec un objet préfixé « Jauge ».
- Dans le record CloudKit `CommunityPolicy` nommé `community-policy-v1`, renseigner l’URL de la page d’assistance dans `supportURL`.

La page d’assistance ouvre la messagerie de l’utilisateur ; aucun message n’est envoyé automatiquement. Les demandes de confidentialité sont adressées au même support. Le symbole publié provient directement de la ressource `BrandSymbol` officielle de l’application iOS.

`privacy.html`, à la racine, renvoie vers la politique de confidentialité de Jauge pour les anciens liens.

`app-ads.txt` est à la racine : Google le lit à la racine du site indiqué sur la fiche App Store.

## Publication

Le dépôt est publié sous le nom `solgys-apps.github.io` dans l’organisation GitHub `Solgys-apps`, avec GitHub Pages configuré sur la branche `main` et le dossier racine.

Les adresses se terminent par un slash (`/lajauge/privacy/`) : c’est normal, et aucune extension `.html` n’est nécessaire. Les liens internes utilisent cette variante.
