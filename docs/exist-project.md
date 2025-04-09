---
layout: default
title: Werk aan Bestaande Projecten
nav_order: 3
---

# Werk aan Bestaande Projecten

Deze gids leidt u door het proces van het integreren van bestaande projecten in uw eigen ontwikkelomgeving, zodat u gemakkelijk kunt ontwikkelen. Volg deze stappen om het project op uw omgeving gereed te maken.

## Inhoud
- [Vereisten](#vereisten)
- [Stap 1: Kloon Repository](#stap-1-kloon-repository)
- [Stap 2: Veranderen Build Platform](#stap-2-veranderen-build-platform)
- [Stap 3: Installeer de XR Provider Plugin](#stap-3-installeer-de-xr-provider-plugin)
- [Belangrijke Informatie](#belangrijke-informatie)

## Vereisten

- **Unity Hub**: Moet al geïnstalleerd zijn.
- **Unity Editor**: Moet al geïnstalleerd zijn met de geschikte versie (Unity 2022.3.60f LTS)
- **IDE**: Er moet een IDE zijn geïnstalleerd
- **Versiebeheer**: Ontwikkelaar moet Git hebben geïnstalleerd (evt. tools zoals GitHub Desktop) en toegevoegd zijn aan de repository


## Stap 1: Kloon Repository

Het klonen van een repository kan op verschillende manieren, hieronder zijn er 2 verschillende manieren: 
via de commandline en via de GitHub Desktop Tool. 

**Methode 1: Commandline**:

1. Via de **Command Prompt** of **Git Bash** navigeer naar de map waar u de repository wilt plaatsen
2. voor de command ```console git clone https://github.com/gebruikersnaam/repository-naam.git ``` uit, maar vervang de URL naar uw repository

**Methode 2: Github Desktop**:

1. Open GitHub Desktop
2. Klik op **File** in de menubalk en selecteer **Clone Repository**
3. Kies de repository die u wilt klonen, via de tab **URL** kan u de URL plakken van de repository die u wilt klonen
4. Kies de lokale map waar u de repository wilt opslaan
5. Klik op **Clone**

## Stap 2: Veranderen Build Platform

Bij het klonen van de repository kan voorkomen dat het project de instellingen niet meeneemt,
Als dit het geval is doe het volgende:

1. In de Unity Hub open het project dat gekloond is door deze te selecteren
2. De Unity Editor wordt opgestart en navigeer naar **File > Build Settings** om dit te openen
3. Onder **Platform** kijk of **Android** is geselecteerd, zo niet klik op **Switch Platform**

## Stap 3: Installeer de XR Provider Plugin

1. In de Unity Editor, navigeer via het menubalk naar **Edit > Project Settings** om de **Project Settings** window te openen
2. Selecteer **XR Plug-in Management**
3. Als de XR Plugin Management niet is geïnstalleerd, selecteer **Install XR Plugin Management**
4. In de **Windows, Mac, Linux settings** tab selecteer **OpenXR**
5. In de **Android Settings** tab, selecteer **OpenXR**
6. Sluit de Project Settings window

> **Note**: Via **Windows > Package Manager** kan u verifiëren of OpenXR plugin is geïnstalleerd


## Belangrijke Informatie

Hier volgt informatie die de ontwikkelaar kan helpen bij enige problemen

> **Troubleshoot**: Bij de eerste keer dat de ontwikkelaar het project opent, ziet het niet de werkelijke scene, maar een compleet nieuwe scene. Als de Ontwikkelaar navigeert naar het **Project** tab en daarin via **Assets > Scenes** gaat naar de werkelijke scene (dit kan een naam hebben zoals **MainScene**) dan ziet de ontwikkelaar de correcte scene waarin gewerkt wordt.



