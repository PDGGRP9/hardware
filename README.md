# hardware

Dossier concernant toute la partie hardware du projet.

## Choix des composants

Les composants ont été sélectionnés principalement pour leur **compacité** : l'objectif étant d'intégrer l'ensemble de l'électronique dans un boîtier de bracelet le plus discret et confortable possible, on a privilégié les modules avec le plus petit form factor disponible pour chaque fonction (carte microcontrôleur, capteurs, alimentation), quitte à sacrifier certaines fonctionnalités superflues pour notre usage.

## Composants utilisés

| Composant | Référence | Fabricant | Rôle | Lien d'achat |
|---|---|---|---|---|
| Carte microcontrôleur | XIAO ESP32S3 | Seeed Studio | Contrôle du bracelet, acquisition des données des capteurs et traitement des mesures | https://www.digikey.ch/fr/products/detail/seeed-technology-co-ltd/113991114/19285530?srsltid=AfmBOorrzzBN7CURkW59EPs6hLaGe72QbhkqyifZ6ozE21W_wURACodI |
| Capteur d'oxymétrie et de rythme cardiaque | SEN0344 | DFRobot | Mesure du rythme cardiaque et du taux d'oxygène dans le sang | https://www.digikey.ch/fr/products/detail/dfrobot/SEN0344/13590869?srsltid=AfmBOooYH3A0KTJ25cAqkZVKTPeWJ1lMRxNGULNLnvJXFMp8pVR536B4 |
| Accéléromètre trois axes | SEN0142 | DFRobot | Détection des mouvements et comptage des pas | https://www.digikey.ch/fr/products/detail/dfrobot/SEN0142/6588492?srsltid=AfmBOoqH7eyKyk71Sckjdzyuh7mFuxvUG2NksLIsK-8Z7FooLzvf2J-3 |
| Batterie | LiPo | | Alimentation autonome du bracelet | https://www.digitec.ch/fr/s1/product/akyga-lp753636-akkupack-x-spezial-akku-lipo-37-v-1000-mah-1000-mah-370-v-batterie-rc-55702794 |
| Bouton poussoir | | | Interaction utilisateur (allumage, mise en veille) | |
| LED | | | Indicateur visuel d'état (charge, notification, etc.) | |

## Schéma de câblage

![Schéma de câblage](images/Schema%20câblage.png)
