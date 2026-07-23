# THIRD PARTY LICENSES - CodexHiddenWind v2.0

Ce logiciel utilise des composants open-source. Leurs licences respectives restent applicables.
CodexHiddenWind lui-même reste sous Licence CircaFrax Proprietary Freeware.

---

## customtkinter
- **Licence:** MIT License
- **Usage:** UI moderne dark
- **Source:** https://github.com/TomSchimansky/CustomTkinter

## Pillow
- **Licence:** HPND License
- **Usage:** traitement d'images JPG/PNG/TIFF/WEBP (miniatures, preview)
- **Source:** https://github.com/python-pillow/Pillow

## tkinter / Python StdLib
- **Licence:** PSF License
- **Usage:** interface de base
- **Source:** https://docs.python.org/3/license.html

## ExifTool by Phil Harvey
- **Licence:** Perl Artistic License 2.0 / GPL (dual license)
- **Usage:** lecture/écriture EXIF / IPTC / XP - moteur des 3 Vents (Blanc/Noir/Rouge)
- **Source:** https://exiftool.org/
- **Binaire inclus:** `ressources/exiftool/exiftool.exe` + `exiftool_files/` (non modifié)
- **Note légale:** Utilisé en exécutable externe via subprocess (agrégation). Non lié statiquement. Code source disponible sur le site officiel. Cette utilisation est explicitement autorisée par l'auteur.

## PyInstaller (outil build)
- **Licence:** GPL-2.0 with exception (outil, non embarqué dans l'exe final)
- **Usage:** conversion .py -> .exe
- **Source:** https://github.com/pyinstaller/pyinstaller

---

## Résumé légal

Toutes ces librairies sont compatibles avec un logiciel propriétaire freeware comme CodexHiddenWind :
- MIT / HPND / PSF / Artistic 2.0 sont permissives
- ExifTool est distribué en binaire non modifié en agrégation (autorisé, pas de copyleft sur votre code)
- PyInstaller est un outil de build, son exception GPL permet la distribution commerciale de l'exe

Vous n'avez pas besoin de distribuer leur code source, seulement cette liste.
Si vous distribuez l'exe, gardez ce fichier `THIRD_PARTY_LICENSES.md` à côté ou dans `_Doc/`.

Généré le 22 juillet 2026 - CircaFrax - pour CodexHiddenWind v2.0
