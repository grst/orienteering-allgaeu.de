+++
date = '2026-08-10'
draft = false
title = 'Mapant: Ganz Bayern als OL-Karte'
tags = ["orientierungslauf", "karten"]
categories = ["news"]
summary = 'Wir haben eine automatisch generierte Orientierungslaufkarte von ganz Bayern erstellt.'
+++

# Mapant: Ganz Bayern als OL-Karte

Wir haben eine automatisch generierte Orientierungslaufkarte von ganz Bayern erstellt.

Bekannt waren solche "Landes-OL-Karten" bisher aus der Schweiz und Skandinavien (siehe [mapant.net](https://mapant.net/) für eine Übersicht). Sie sind nützlich zum Training, oder um neue OL Gebiete zu entdecken, ersetzen aber nicht die Arbeit der Kartenaufnehmer zum Erstellen einer "richtigen" OL-Karte.

![Übersicht der Mapant-Karte von Bayern](/img/posts/2026-08-10_mapant-bayern/overview.webp)

Als Grundlage für die Karte dienen die vom bayerischen Vermessungsamt zur Verfügung gestellten Laserscan-Daten und Geodaten der OpenStreetMap. Diese wurden mit dem Tool Karttapullautin in die OL-Karte umgewandelt. Die Web-App zum Anzeigen der Karte wurde mit Hilfe von KI entwickelt.

![Detailausschnitt der Mapant-Karte](/img/posts/2026-08-10_mapant-bayern/detail.webp)

Um die 15TB Laserscandaten zu verarbeiten, wurden auf einem Hochleistungsserver innerhalb von 27 Stunden etwa 5000 CPU Stunden Rechenleistung verwendet. Ein gewöhnlicher Laptop müsste hierfür etwa einen Monat lang durchlaufen. Insgesamt haben wir etwa 3,5 Tage Entwicklungsarbeit in das Projekt gesteckt.

Die Karte steht unter [mapant.orienteering-allgaeu.de](https://mapant.orienteering-allgaeu.de/) zur Verfügung. Wer an technischen Details interessiert ist, findet diese auf [GitHub](https://github.com/grst/mapant-bayern).
