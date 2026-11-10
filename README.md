# Relief des zones de Radar roches

Données publiées pour l'appli [Radar roches](https://ymca-dev-wow.github.io/radar-roches/) : relief Litto3D® (Shom – IGN,
Licence Ouverte 2.0) des zones de navigation, en tuiles PNG mises bout à bout.

- `<zone>/relief.json` : index `{ zoom, packs: [{nom, taille}], tuiles: {"x/y": [paquet, début, longueur]} }`
- `<zone>/relief_N.pack` : PNG des tuiles (moins de 45 Mo par paquet)

Généré par `outils/preparer_site.py` du projet ; séparé du site principal car il ne change qu'à l'ajout d'une zone.
