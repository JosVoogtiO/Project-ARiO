---
layout: default
title: Get Started
nav_order: 2
---

# Nieuw Project

Deze gids leidt u door het proces van het maken van een nieuw project in Unity om uiteindelijk AR-applicaties te ontwikkelen voor de Meta Quest 3.
Volg deze stappen om je projectopzet gereed te maken en begin met het maken van geweldige projecten.

## Inhoud
- [Vereisten](#vereisten)
- [Stap 1: Creëren nieuw project](#stap-1-creeren-nieuw-project)
- [Stap 2: Opzetten Build Platform](#stap-2-opzetten-build-platform)
- [Stap 3: Installeer de XR Provider Plugin](#stap-3-installeer-de-xr-provider-plugin)
- [Stap 4: Installeer de SDK](#stap-4-installeer-de-sdk)
- [Stap 5: Configureer Project met Project Setup Tool](#stap-5-configureer-project-met-project-setup-tool)

## Vereisten

- **Unity Hub**: Moet al geïnstalleerd zijn.
- **Unity Editor**: moet al geïnstalleerd zijn voor de geschikte versie (Unity 2022.3.60f LTS)

## Stap 1: Creëren Nieuw Project

Het juist opzetten van je project vanaf het begin bespaart je veel tijd en moeite in latere ontwikkelingsfasen.

1. Open de Unity Hub
2. op de projects tab, selecteer "New Project"
3. Selecteer de Unity versie die je wilt gebruiken (Unity 2022.3.60f LTS)
4. Kies de "Universal 3D" template.
5. Geef het project een naam en een locatie om op te slaan.
6. Indien nodig selecteer ook ["Connect to Unity Cloud"](https://unity.com/products/unity-cloud) en ["Use Unity version Control"](https://unity.com/how-to/redeem/version-control) mocht dit van toepassing zijn voor het project.
7. Selecteer "Create Project"

## Stap 2: Opzetten Build Platform

Het platform waar de Meta Quest headsets zijn gebouwd is Android, en de build output is een .apk (Android Executable) file

1. In de Unity Editor navigeer naar **File > Build Profiles** en open dit.
2. Onder **Platform** selecteer **Android** en selecteer **Switch Platform**


## Stap 3: Installeer de XR Provider Plugin

1. Open het project in de Unity Editor (als dit nog niet gedaan is)
2. Via de top menu, navigeer naar **Edit > Project Settings** om de **Project Settings** window te openen.
3. Selecteer **XR Plug-in Management**.
4. Als de XR Plugin Management niet is geïnstalleerd, selecteer **Install XR Plugin Management**.
5. In de **Windows, Mac, Linux settings** tab selecteer **OpenXR**.
6. In de **Android Settings** tab, selecteer **OpenXR**.
7. Sluit de Project Settings window

> **Note**: Via **Windows > Package Manager** kan je verifiëren of OpenXR plugin is geïnstalleerd

## Stap 4 Installeer de SDK

De Meta SDK's zijn makkelijk te importeren in je project.

1. Ga naar de [Unity Asset Store](https://assetstore.unity.com/publishers/25353), en login via je Unity account
2. Navigeer naar de [Meta XR All-in-One SDK](https://assetstore.unity.com/packages/tools/integration/meta-xr-all-in-one-sdk-269657) pagina
3. Selecteer **Add to My Assets** om het pakket toe te voegen aan jouw assets
4. Selecteer **Open in Unity** om de **Package Manager** window te openen in de Unity Editor.
5. In de **Package manager** window, in the rechterbovenhoek van window, selecteer **Install** om de SDK's te installeren.

> **Note**: Deze stappen zijn ook te volgen voor andere SDK's.

## Stap 5: Configureer Project met Project Setup Tool

De Project Setup Tool is een Unity Editor extensie, handig voor Unity projecten voor het ontwikkelen van XR-toepassingen op de Meta

1. Voor Android open de Project Setup Tool in de Unity Editor, Navigeer naar **Meta > Tools > Project Setup Tool**.
2. Om alle issues te verhelpen, selecteer **Fix All**

> **Note**: Daarnaast zijn er ook instellingen die handig kunnen zijn bij het ontwikkelen, maak bewuste keuze of je de instelling wilt hebben en selecteer **Apply* of **Apply All**


