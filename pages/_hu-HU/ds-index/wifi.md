---
lang: hu-HU
layout: wiki
section: ds-index
category: reference
title: Wi-Fi
description: Információk a Wi-Fi használatáról Nintendo DS-en
---

- Nintendo DS applikációkból csak WEP és nyílt WiFi használható
- A Nintendo DSi bővített/exkluzív alkalmazások esetében rendelkezel a WPA2 támogatás kiegészítéssel

Hotspotok használhatók, így nem szükséges megváltoztatnod a routered konfigurációját.

### Hotspot létrehozása
Találhatók útmutatók a GBATemp-en arról, hogyan hozz létre egy DS játék kompatibilis hotspot-ot macOS és Linux számítógépekre. Ha Windows-on dolgozol használhatsz egy Linux live bootolást is.
- [macOS](https://gbatemp.net/threads/571658)
- [Linux](https://gbatemp.net/threads/543283)

### Nintendo DS WFC helyreállítás

1. Indítsd el a Nintendo WFC beállításokat
1. Csatlakozz a hozzáférési pontodhoz
1. Állítsd be az elsődleges (primary) DNS értéket az alábbiak valamelyikére, attól függően, hogy melyik szolgáltatást szeretnéd használni:
   - **Wiimmfi** - `164.132.44.106`
   - **AltWFC/WFCZwei** - `172.104.88.237` or `104.131.93.87`
   - **BenFi** - `24.218.177.103`
   - **Twilit WFC** - `34.66.49.81`
1. Állítsd be az `1.1.1.1` címet másodlagos DNS-nek
1. Szükséged lehet NoSSL patchelésre a játékodban, függően a játéktól
