# <u>ToDo-Applikation</u>

## Projektbeschreibung

Dies ist eine einfache ToDo-Applikation, die mit Node.js erstellt wurde. Sie wird in einem Docker-Container bereitgestellt und kann lokal ausgeführt werden. Dieses Projekt kombiniert die Nutzung von Markdown, Git, GitHub und Docker.

## Voraussetzungen

- Git
- Docker

### Git und Docker installieren

Falls sie Git und/oder Docker nicht bereits installiert haben, folgen sie den Instruktionen unter den folgenden Links:

- [Git Installation](https://git-scm.com/downloads)
- [Docker Installation](https://docs.docker.com/desktop/install/windows-install/)

## Installation

### 1. Repository klonen

Zuerst müssen sie das Repository auf Ihren Computer klonen. Verwenden sie dazu den folgenden Befehl in einem Ordnerverzeichnis Ihrer wahl:
Zum einfügen in Git benötigen Sie die Tastenkombination Shift+Insert.

```bash
git clone https://github.com/dein-nutzername/docker-nodejs-sample
```

### 2. Applikation ausführen

Folgen sie dieser [Anleitung](https://docs.docker.com/guides/language/nodejs/containerize/) ab dem Schritt "Initalize Docker assets"
um die Applikation zu starten. Am besten nutzten sie dafür die Eingabeaufforderung von Windows und stellen sie sicher das beim starten Sie die Docker Desktop App geöffnet haben. Wenn sie online ist wird sie unter dem Link [http://localhost:3000](http://localhost:3000) erreichbar sein.

---

## FAQ

#### Ich krieg eine Fehlermeldung beim "docker init" Befehl.
Meistens ist hier das Problem das Docker nicht geöffnet ist. Um diesen Fehler zu beheben, öffnen sie Docker auf Ihrem Desktop.

<br>

#### Ich habe eine Fehlermeldung währen des "docker compose up --build" Befehl.
Wenn dies auftritt und Sie es in Git ausgeführt haben, sollten Sie es in der Eingabeaufforderung versuchen. Vergessen Sie nicht in das
richtige Ordnerverzeichnis zu wechseln. Falls dies nicht geht, führen sie den Befehl direkt im Terminal von Visual Studio
Code aus. Vergessen Sie auch da nicht, den richtigen Ordner zu öffnen.[Visual Studio Code Download](https://code.visualstudio.com/download)

<br>

#### Sehen sie meine Daten?
Nein, alles was Sie bei der To-Do Liste eintragen ist auf Ihrem Computer gespeichert daher Sie die Website selber Hosten.

<br>

---

<br>

## Viel Spass beim Programmieren :D
