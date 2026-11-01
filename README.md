### Salut 👋

Domotique **Home Assistant** et **ESPHome** : du matériel détourné, du local plutôt que du cloud, et de l'énergie optimisée (EDF Tempo, solaire, batterie).

#### Projets

| Projet | Description |
|---|---|
| [airton-esphome](https://github.com/inoxas78/airton-esphome) | Clims **Airton** (monosplits Tuya et bi-splits 7A 7A) pilotées en local avec ESPHome, sans dongle. Décodage des protocoles, compteur d'énergie caché, orchestrateur chauffage clims / gaz (Tado) selon **Tempo**, présence et solaire |
| [divoompixoo64_WYSIWYG](https://github.com/inoxas78/divoompixoo64_WYSIWYG) | Pixoo Designer OS : éditeur WYSIWYG et moteur de rendu pour **Divoom Pixoo 64** sous Home Assistant |
| [HA-E-Ink-PhotoFrame](https://github.com/inoxas78/HA-E-Ink-PhotoFrame) | Cadre photo **e-paper** sur ESP32 |
| [HA-COLOREINK-ESPHOME](https://github.com/inoxas78/HA-COLOREINK-ESPHOME) | Cadre **e-ink 7 couleurs** ESPHome pour afficher les infos de la maison |
| [esp32obdford](https://github.com/inoxas78/esp32obdford) | Suivi d'un véhicule via un module OBD Bluetooth **Vlinker** et un ESP32 |

#### Dans ce dépôt

- [`chauffe-eau-solaire.yaml`](chauffe-eau-solaire.yaml) : blueprint Home Assistant qui pilote un chauffe-eau la nuit et sur surplus solaire, avec une limite quotidienne.
- [`sensors.yaml`](sensors.yaml) : capteurs associés.
