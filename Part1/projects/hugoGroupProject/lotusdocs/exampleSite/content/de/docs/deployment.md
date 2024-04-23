---
weight: 100
date: "2023-05-03T22:37:22+01:00"
draft: false
author: "Joao Martins"
title: "Deployment"
icon: "rocket_launch"
toc: true
description: "Ein Leitfaden zum Bereitstellen einer Hugo-Website"
publishdate: "2023-05-03T22:37:22+01:00"
tags: ["Beginners"]
---

# Bereitstellen einer Hugo-Website mit Netlify

Dieser Leitfaden hilft Ihnen dabei, Ihre Hugo-Website mithilfe von Netlify zu veröffentlichen, einer Plattform für die Bereitstellung von statischen Websites.

## Bevor Sie beginnen

Stellen Sie sicher, dass Sie Folgendes haben:

- Ein fertiges Hugo-Website-Projekt.
- Ein angemeldetes Konto bei Netlify.
- Hugo auf Ihrem Computer installiert.

## Schritte

### 1. Registrieren Sie sich bei Netlify

Falls noch nicht geschehen, erstellen Sie ein Konto bei Netlify. Das geht schnell und ist kostenlos.

### 2. Fügen Sie Ihre Website zu Netlify hinzu

Gehen Sie zur Seite "Sites" von Netlify und klicken Sie auf "Neue Site von Git".

Sie können die Netlify-Dokumentation überprüfen [Netlify Docs](https://docs.netlify.com/get-started/).

### 3. Verbinden Sie Ihr Repository

Wählen Sie Ihren Git-Anbieter (wie GitHub) aus. Netlify wird Sie durch die Verbindung Ihres Repositorys führen.

### 4. Konfigurieren Sie die Build-Einstellungen

Netlify erkennt automatisch Ihre Hugo-Website. Überprüfen Sie die Build-Einstellungen und passen Sie sie bei Bedarf an.

### 5. Veröffentlichen Sie Ihre Website

Option 1: Klicken Sie auf "Website veröffentlichen". Netlify beginnt mit dem Erstellen Ihrer Hugo-Website.
Option 2: Navigieren Sie zum Ordner, in dem sich Ihre Hugo-Website befindet. Installieren Sie Netlify mit:
```shell
npm install -g netlify-cli
```
Nach Abschluss der Installation geben Sie ein:
```shell 
netlify deploy prod
```
und folgen Sie den Anweisungen.

### 6. Greifen Sie auf Ihre Website zu

Nach Abschluss des Builds gibt Ihnen Netlify eine URL, unter der Sie Ihre veröffentlichte Website anzeigen können.

## Fazit

Sie haben Ihre Hugo-Website erfolgreich mit Netlify veröffentlicht! Entdecken Sie Netlifys zusätzliche Funktionen, um Ihre Website weiter zu verbessern.