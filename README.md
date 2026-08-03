# Matcha - téléchargements

Binaires publics de **Matcha**, le système d'exploitation des développeurs.
Le code source est privé ; ce dépôt ne contient que ce qui s'installe.

## Télécharger

Prends la [dernière release](../../releases/latest) et l'archive de ta plateforme.

| Plateforme | Fichier | Note |
|---|---|---|
| macOS | `Matcha-<version>.dmg` | signé Developer ID et notarisé par Apple |
| Windows | `matcha-windows-<version>.zip` | |
| Android | `matcha-<version>.apk` | installation manuelle |

## Mises à jour automatiques

macOS se met à jour tout seul via [Sparkle](https://sparkle-project.org/), qui
lit l'`appcast.xml` publié dans la release la plus récente. Le flux est signé
en EdDSA : l'app refuse une mise à jour dont la signature ne correspond pas.

L'URL du flux ne change jamais de version en version :

    https://github.com/devganeden/matcha-releases/releases/latest/download/appcast.xml

## Le site

<https://matcha.ganeden.eu>

