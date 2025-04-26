# PixelToMac

**Mini application pour transférer facilement le contenu d'un smartphone Pixel 6a vers un MacBook Air M2.**  
L'objectif est d'éviter d'utiliser Android File Transfer ou OpenMTP, souvent instables.

---

## Objectif

- Transférer rapidement photos, vidéos, documents du Pixel 6a vers le MacBook Air en USB.
- Fiable, simple, sans Wi-Fi.
- Basé sur l'outil `simple-mtpfs` pour monter le téléphone comme un disque dur externe.

---

## Solution technique

- Utilisation de `simple-mtpfs` pour accéder au stockage du téléphone via MTP.
- Script ou petite application pour automatiser :
  - Le montage du Pixel.
  - La copie automatique ou sélective des fichiers.

---

## Plan d'action

1. Installer Homebrew sur Mac (si nécessaire).
2. Installer `simple-mtpfs` via Homebrew.
3. Brancher le Pixel en mode **Transfert de fichiers**.
4. Tester le montage manuel.
5. Créer un script pour automatiser la copie.
6. Améliorations possibles :
   - Interface graphique simple.
   - Sélection des fichiers avant transfert.
   - Notification de fin de transfert.

---

## Prérequis

- macOS (MacBook Air M2).
- Câble USB pour connecter le Pixel 6a.
- Homebrew installé.
- `simple-mtpfs` installé.

---

## Licence

Projet personnel. Libre d'utilisation pour usage personnel.

---

## Auteur

- [lyzhpar](https://github.com/lyzhpar)