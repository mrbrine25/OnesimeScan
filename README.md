<img width="1600" height="500" alt="banner-scan" src="https://github.com/user-attachments/assets/acd96967-06f2-4011-be8e-1cffcaef45d1" />


**Le logiciel de numérisation d'[Onésime](https://mrbrine25.github.io/Onesime/), pour les généalogistes et les archivistes.**

![Version](https://img.shields.io/github/v/release/mrbrine25/OnesimeScan?style=flat-square&color=8b5cf6&label=version)
![Plateformes](https://img.shields.io/badge/Windows%20%7C%20macOS%20%7C%20Linux-gratuit-f97316?style=flat-square)
[![Discord](https://img.shields.io/badge/Discord-Rejoindre-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/N8ayZbzeye)

</div>

Posez plusieurs photos sur la vitre de votre scanner : Onésime Scan trouve chacune d'elles, la redresse, la remet dans le bon sens et l'enregistre dans un fichier à part, directement dans vos dossiers d'archive. Tout se fait sur votre ordinateur : rien n'est envoyé sur internet.

---

## Téléchargement

Sur la **[dernière version](https://github.com/mrbrine25/OnesimeScan/releases/latest)**, tout en bas (« Assets »), prenez **un seul** fichier :

| Votre ordinateur | Fichier à télécharger |
|---|---|
| Windows 10 / 11 | `OnesimeScan-…-Setup.exe` |
| Mac récent (puce Apple M1, M2, M3…) | `OnesimeScan-…-mac-arm64.dmg` |
| Mac Intel (avant 2020) | `OnesimeScan-…-mac-x64.dmg` |
| Linux : Ubuntu, Mint, Debian | `OnesimeScan-…-linux-amd64.deb` (double-clic pour l'installer) |
| Linux : autres distributions | `OnesimeScan-…-linux-x86_64.AppImage` (à rendre exécutable ; demande libfuse2) |

Les autres fichiers (`latest.yml`, `.blockmap`…) servent aux mises à jour automatiques : inutile de les télécharger.

> **Windows** — À la première ouverture, Windows peut afficher un avertissement « application inconnue ». Cliquez sur **Informations complémentaires → Exécuter quand même**. Les versions suivantes s'installent ensuite toutes seules.

> **Linux** — Le `.deb` s'ouvre avec l'installateur de logiciels d'Ubuntu ou de Mint. Les mises à jour arrivent ensuite toutes seules.

> **Mac** — Au premier lancement, faites **clic droit sur l'app → Ouvrir**, puis confirmez. macOS demandera aussi l'autorisation d'accéder au **réseau local** : acceptez, c'est ce qui permet de trouver votre scanner.

---

## Ce qu'il sait faire

**Numériser**
- Trouve tout seul les scanners du réseau (AirScan / eSCL : la plupart des imprimantes multifonctions récentes) ; scanners USB sous Windows
- Aperçu puis numérisation **en direct** : l'image apparaît pendant que le scanner avance
- Qualité au choix, ou personnalisée dans les limites du scanner

**Plusieurs photos à la fois**
- Chaque photo posée sur la vitre est trouvée, bords blancs dentelés compris, et enregistrée à part
- Redressement automatique, cadres ajustables à la souris
- Photos couchées ou à l'envers **remises dans le bon sens** d'après les visages

**Retouches**
- Raviver les couleurs passées, contraste automatique
- Effacer l'ombre de la reliure d'un registre ou d'une feuille gondolée
- Retirer la trame d'impression des cartes postales et des journaux
- Netteté, réduction du grain

**Enregistrer**
- JPEG, TIFF (sans perte, pour la conservation), PNG
- **PDF de plusieurs pages**, avec texte cherchable pour l'imprimé et la machine à écrire
- Noms automatiques avec compteur (`Album3-photo+-1922` → `Album3-photo28-1922`)
- Profils couleur, 16 bits si le scanner le permet

---

## Vos données

Onésime Scan fonctionne hors ligne. La reconnaissance des visages et la lecture du texte se font sur votre ordinateur, avec des modèles fournis dans l'application. Il se connecte seulement pour chercher votre scanner sur votre réseau local et, sous Windows et Linux, pour vérifier au démarrage s'il existe une nouvelle version (sur GitHub, sans rien envoyer vous concernant).

---

## Licence

Gratuit pour un usage personnel. Redistribution, revente ou exploitation commerciale interdites sans autorisation écrite. Texte complet : [LICENSE](LICENSE).

Développé par **Amélien BRISEBARD**, auteur d'[Onésime](https://github.com/mrbrine25/Onesime).
