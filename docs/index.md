---
layout: default
title: Setup Guide
nav_order: 1
---

# Setup Guide

Deze gids helpt u bij het opzetten van een ontwikkelomgeving voor AR-applicaties op de Meta Quest 3. Volg onderstaande stappen om uw ontwikkelomgeving volledig gereed te maken.

## Inhoud
- [Vereisten](#vereisten)
- [Stap 1: Installeer Unity Hub](#stap-1-installe-unity-hub)
- [Stap 2: Installeer Unity Editor](#stap-2-installeer-unity-editor)
- [Stap 3: Configureer IDE](#stap-3-configureer-ide)

## Vereisten

- **Besturingssysteem**: Windows 10/11 (64-bit), macOS 10.15 of nieuwer, of Ubuntu 20.04/22.04
- **CPU**: Ondersteuning voor SSE2 instructieset
- **GPU**: Grafische kaart met DX10, DX11, of DX12 mogelijkheden
- **RAM**: Minimaal 8GB, aanbevolen 16GB of meer
- **Opslagruimte**: Tenminste 10GB vrije ruimte voor installatie
- **Versiebeheer**: Dit document behandelt niet het installeren van Git of tools zoals GitHub Desktop, hoewel deze wel vereist zijn als u versiebeheer wilt toepassen.

## Stap 1: Installeer Unity Hub

De Unity Hub is een management tool dat helpt met het organiseren van Unity projecten en het beheren van verschillende Unity Editor versies.

1. Ga naar de [Unity Download pagina](https://unity.com/download)
2. Klik de **Download** knop voor de geschikte OS (Windows, Linux, Mac)
3. Voer de installer uit en volg de instructies
4. Lanceer Unity Hub na installatie
5. Login met uw Unity ID (creëer er een als u nog geen ID hebt)

> **Note**: Unity biedt verschillende licentietypen. Voor persoonlijk gebruik of kleine teams is de Personal-licentie gratis. Voor commerciële projecten heeft u mogelijk een andere licentie nodig.

## Stap 2: Installeer Unity Editor

Wanneer de Unity Hub is geïnstalleerd, moet u de Unity Editor installeren.

1. In Unity Hub, ga naar de **Installs** tab
2. Klik op de **Install Editor** knop
3. Selecteer **Unity (2022.3.60f1) LTS (Long Term Support)** voor de stabiliteit
4. Selecteer de volgende modules om te installeren:
   - Microsoft Visual Studio Community 2022
   - Android Build Support
5. Klik **Install** en wacht tot dat de installatie klaar is

> **Note**: Het selecteren van de IDE Microsoft Visual Studio Community 2022 is aangeraden, maar mocht u een voorkeur hebben kunt u een andere IDE installeren.

## Stap 3: Configureer IDE

Het opzetten van de IDE die u wilt gebruiken. Hieronder Visual Studio.
Kijk via de officiële docs van uw gekozen IDE voor Unity Development modules/extensions

1. Lanceer Visual Studio Installer
2. Bij de eerste keer dat u de installer opstart moet u de licentievoorwaarden accepteren
3. Klik bij Visual Studio Community 2022 op **Modify**
4. In de **Workloads** tab, vink de optie **Game Development with Unity** aan
5. Navigeer naar de tab **Individual Component**
6. Zoek naar **Unity**
7. Vink de optie **Visual Studio Tools for Unity** aan
8. Klik rechts onderin of **Modify**

> **Note**: Na het modificeren van uw IDE kan het zijn dat de computer opnieuw moet worden opgestart.
