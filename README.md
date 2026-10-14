# Camify – FS2024

Caméras cinématiques pour **Microsoft Flight Simulator 2024** : ralenti autour de l'avion avec
plans aléatoires, flyby (la caméra attend l'avion sur sa trajectoire) et tour de contrôle (caméra
en bord de la piste d'atterrissage). Chaque atterrissage est enregistré et noté : revoyez-le sur un
graphe ou rejouez-le dans MSFS, filmé par ces caméras. Caméras et replay se pilotent aussi depuis le
navigateur du téléphone, sur le réseau local. Raccourci clavier global, thème clair/sombre, français,
anglais et espagnol. Aucun compte, aucune donnée envoyée.

Cinematic cameras for **Microsoft Flight Simulator 2024**: slow-motion shots around the aircraft,
flyby (the camera waits for the aircraft on its path) and control tower (camera beside the
landing runway). Every landing is recorded and rated: review it on a graph or replay it in MSFS,
filmed by these cameras. Cameras and replay can also be driven from the phone's web browser, on the
local network. Global keyboard shortcut, light/dark theme, French, English and Spanish. No account,
no data sent.

## Téléchargement / Download

👉 **[Dernière version / Latest release](https://github.com/kairhosen/Camify-releases/releases/latest)** —
`Camify.exe`, Windows 10/11 64 bits, sans installation / no installation.

Vérifier le fichier / Verify the file (PowerShell) — l'empreinte SHA-256 est affichée sur la page
de la version / the SHA-256 is shown on the release page:

```powershell
(Get-FileHash .\Camify.exe).Hash
```

## Composants tiers / Third-party components

`Camify.exe` intègre, sans modification, `SimConnect.dll` du Microsoft Flight Simulator 2024 SDK
(© Microsoft Corporation, fourni « tel quel »), soumis aux termes de licence du SDK :
[MSFS-SDK-EULA.pdf](MSFS-SDK-EULA.pdf). Voir [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).

`Camify.exe` embeds, unmodified, `SimConnect.dll` from the Microsoft Flight Simulator 2024 SDK
(© Microsoft Corporation, provided "as is"), subject to the SDK license terms:
[MSFS-SDK-EULA.pdf](MSFS-SDK-EULA.pdf). See [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).

Ce dépôt ne contient que les versions publiées ; le code source n'est pas public.
This repository only hosts published releases; the source code is not public.

© 2026 kairhosen. Tous droits réservés / All rights reserved. Application indépendante, non
affiliée à Microsoft / Independent application, not affiliated with Microsoft.
