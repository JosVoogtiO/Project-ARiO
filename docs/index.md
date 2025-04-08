---
layout: default
title: Setup Guide
nav_order: 1
---

# Setup Guide

Deze gids leidt u door het proces van het opzetten van de ontwikkelomgeving voor het maken van AR-applicaties voor de Meta Quest 3.
Volg deze stappen om uw ontwikkelomgeving gereed te maken en begin met het maken van geweldige projecten.

## Inhoud
- [Vereisten](#vereisten)
- [Stap 1: Installeren Unity Hub](#stap-1-installeren-unity-hub)
- [Stap 2: Installeer Unity Editor](#stap-2-installeer-unity-editor)
- [Stap 3: Configureer IDE](#stap-3-configureer-ide)

## Vereisten

- **Besturingssysteem**: Windows 10/11 (64-bit), macOS 10.15 of nieuwer, of Ubuntu 20.04/22.04
- **CPU**: Ondersteuning voor SSE2 instructieset
- **GPU**: Grafische kaart met DX10, DX11, of DX12 mogelijkheden
- **RAM**: Minimaal 8GB, aanbevolen 16GB of meer
- **Opslagruimte**: Tenminste 10GB vrije ruimte voor installatie
- **Versiebeheer**: In dit document wordt niet behandeld het installeren van Git of van tools zoals GitHub Desktop, maar dit zijn wel vereisten als je versiebeheer wilt toepassen.

## Stap 1: Installeren Unity Hub

De Unity Hub is een management tool dat helpt met het organiseren van Unity projecten en het beheren van verschillende Unity Editor versies.

1. Ga naar de [Unity Download pagina](https://unity.com/download)
2. Klik de "Download" knop voor de geschikte OS (Windows, Linux, Mac)
3. Voer de installer uit en volg de instructies
4. Lanceer Unity Hub na installatie
5. Login met je Unity ID (creëer er een als je nog geen ID hebt)

> **Note**: Unity biedt verschillende licentietypen. Voor persoonlijk gebruik of kleine teams is de Personal-licentie gratis. Voor commerciële projecten hebt u mogelijk een andere licentie nodig.

## Stap 2: Installeer Unity Editor

Wanneer de Unity Hub is geinstalleerd, moet je de Unity Editor installeren.

1. In Unity Hub, ga naar de **Installs** tab
2. Klik op de **Install Editor** knop
3. Selecteer "Unity (2022.3.60f1) LTS" (Long Term Support) voor de stabiliteit
4. Selecteer de volgende modules om te installeren:
   - Microsoft Visual Studio Community 2022 (of gebruik een andere IDE)
   - Android Build Support
5. Klik **Install** en wacht tot dat de installatie klaar is

## Stap 3: Configureer IDE

Het opzetten van de IDE die je wilt gebruiken. Hieronder Visual Studio.
Kijk via de officiele docs van je gekozen IDE voor Unity Development modules/extensions

**IDE Setup Visual Studio**:
   1. Lanceer Visual Studio Installer
   2. Klik bij Visual Studio Community 2022 op "Modify"
   3. Navigeer naar de tab "Individual Components"
   4. Zoek naar "Unity"
   5. Vink de optie "Visual Studio Tools for Unity" aan
   6. Klik rechtsonderin of "Modify"

> **Note**: Na het modificeren van je IDE kan het zijn dat de computer op nieuw moet worden gestart.
