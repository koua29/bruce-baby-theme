# 🧸 Baby Toy — Bruce Theme

[![Bruce firmware](https://img.shields.io/badge/firmware-Bruce-8A2BE2?logo=github)](https://github.com/BruceDevices/firmware) [![Device](https://img.shields.io/badge/device-LilyGO%20T--Embed%20CC1101-1E90FF)](https://github.com/BruceDevices/firmware) [![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

> **EN** — A bright, playful **kids-toy** UI theme for the **[Bruce firmware](https://github.com/BruceDevices/firmware)** on the LilyGO T-Embed CC1101 (320×170). Each menu is a **horizontal carousel** — previous · **current** · next — with a colorful cartoon picto on a candy badge and a chunky label. The current label takes its own picto's color with a bold black outline. Two variants included.

> **FR** — Un thème UI **jouet enfant** coloré et fun pour le firmware **[Bruce](https://github.com/BruceDevices/firmware)** sur LilyGO T-Embed CC1101 (320×170). Chaque menu est un **carrousel horizontal** — précédent · **courant** · suivant — avec un picto cartoon coloré sur une pastille candy et un gros libellé. Le libellé courant reprend la couleur de son picto, contour noir. Deux variantes incluses.

| 🖥️ Sur l'appareil |
|:---:|
| ![Baby Toy on device](docs/device-toy1.jpg) |

## 🎨 Deux variantes

| | Aperçu |
|---|---|
| **`Baby_Toy`** — cadre tablette jouet complet (bandeau PLAY/LEARN/SONGS) | ![toy1](docs/grid-toy1.png) |
| **`Baby_Toy2`** — sans cadre, fond rose, **pictos plus gros** | ![toy2](docs/grid-toy2.png) |

<img src="docs/device-toy2.jpg" width="420" alt="Baby_Toy2 on device" />

## ✨ Détails

- 🎠 Carrousel horizontal (préc. petit · **courant grand/vif** · suiv. petit), texte **intégré dans l'image** (`label: 0`).
- 🍬 Pictos **OpenMoji** cartoon sur pastilles candy colorées (une couleur par catégorie), reflet glossy.
- 🔠 Libellé courant en **couleur du picto + contour noir** (Comic Sans), voisins atténués.
- 🔢 Voisins peints selon l'**ordre réel** du menu Bruce T-Embed CC1101 (FM inclus).

## 📦 Contenu

Chaque variante contient **4 tailles** × **16 PNG** + son `.json` :

| Dossier | Image | Écran cible |
|---|---|---|
| `105px/` | 240×105 | M5StickC Plus (240×135) |
| `140px/` | 320×140 | **T-Embed CC1101 / Cardputer (320×170)** |
| `180px/` | 320×180 | écrans ~320×210 |
| `192px/` | 320×192 | écrans ~320×222 |

> ℹ️ **Barre d'état** — Bruce réserve **30 px en haut** (heure / SD / WiFi / batterie). La bonne taille = **hauteur écran − 30**. Pour le **T-Embed CC1101 → `140px`**.

## 🚀 Installation

1. Copie **`Baby_Toy`** et/ou **`Baby_Toy2`** à la racine de la carte SD.
2. Sur l'appareil : **Config → UI Theme → `Baby_Toy/140px/Theme_Baby_Toy.json`** (ou `Baby_Toy2/140px/Theme_Baby_Toy2.json`).
3. Via WiFi : **Files → WebUI**, upload le dossier, puis sélectionne le `.json`.

## 🛒 Matériel / Hardware

Accessoires utiles pour ce projet — liens affiliés Amazon :

| [<img src="docs/amazon-B0GXB24SRR.jpg" width="200" alt="T-Embed CC1101 screen protector">](https://www.amazon.com/dp/B0GXB24SRR?linkCode=ll2&tag=koua29-20&ref_=as_li_ss_tl) | [<img src="docs/amazon-B0C1FCZM94.jpg" width="200" alt="433 MHz SMA antenna (2-pack)">](https://www.amazon.com/dp/B0C1FCZM94?linkCode=ll2&tag=koua29-20&ref_=as_li_ss_tl) | [<img src="docs/amazon-B0B7NVMBPL.jpg" width="200" alt="SanDisk 64 GB microSD (2-pack)">](https://www.amazon.com/dp/B0B7NVMBPL?linkCode=ll2&tag=koua29-20&ref_=as_li_ss_tl) |
|:---:|:---:|:---:|
| 🛡️ **[T-Embed CC1101 screen protector](https://www.amazon.com/dp/B0GXB24SRR?linkCode=ll2&tag=koua29-20&ref_=as_li_ss_tl)**<br><sub>Lamshaw, film TPU ×6</sub> | 📡 **[433 MHz SMA antenna (2-pack)](https://www.amazon.com/dp/B0C1FCZM94?linkCode=ll2&tag=koua29-20&ref_=as_li_ss_tl)**<br><sub>Antenne sub-GHz pour la radio CC1101</sub> | 💾 **[SanDisk 64 GB microSD (2-pack)](https://www.amazon.com/dp/B0B7NVMBPL?linkCode=ll2&tag=koua29-20&ref_=as_li_ss_tl)**<br><sub>Pour les thèmes, scripts et captures Bruce</sub> |

<sub>En tant que Partenaire Amazon, je réalise un bénéfice sur les achats remplissant les conditions requises. · As an Amazon Associate I earn from qualifying purchases.</sub>

## 🎨 Crédits

- Thème & fond par **koua29**.
- Pictos : **[OpenMoji](https://openmoji.org)** — licence **CC BY-SA 4.0** (les pictos et images de menu qui les incorporent restent sous CC BY-SA 4.0).
- Police : **Comic Sans MS**. Tourne sur l'excellent **[Bruce firmware](https://github.com/BruceDevices/firmware)**.

## ☕ Un café ?

<img src="docs/paypal-qr.png" width="180" alt="PayPal" />

## 📄 Licence

Code & fond du dépôt sous **MIT** (voir [LICENSE](LICENSE)). Pictos OpenMoji sous **CC BY-SA 4.0**.
