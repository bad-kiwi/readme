# Titel der Webanwendung/des Projekts
=====

Von [Autor/Firma](URL).

Eine kurze Beschreibung der Anwendung direkt zu Beginn. Ein Projekt ohne Dokumentation ist kein Projekt. Die Dokumentation findet im Format einer Markdown (README) Datei statt. So kann sie mit dem Projekt via SVN oder GIT versioniert werden und ist über alle Platformen von jedem auslesbar. Diese Vorlage lebt von Ideen, also bitte diese teilen, damit sie unter Umständen auch hier aufgenommen werden können.



## Inhaltsverzeichnis

 - [Installaltion](#installation)
 - [Verwendung](#verwendung)
 - [Konfiguration](#konfiguration)
 - [Informationen](#informationen)
 - [Versionierung](#versionierung)
 - [Autoren](#autoren)
 - [Copyright und Lizenz](#copyright-und-lizenz)



## Installation

Die Anwendung kann wie folgt installiert werden. Kurze Beschreibung der Installation. Immer daran denken, dass jemand drittes mit diesem Dokument in der Lage sein sollte, den Installationsprozess durchzuführen.

```console
ebenso wichtig sind Code-Beispiele
wie auch direkt die Befehle für die Konsole
```

Zum installieren reicht der folgende Befehl im Projekt-Root auf der Konsole:

```console
bundle install
```

Anschließend noch die Anwendung initialisieren:

```console
php generate my_example_gem:install
```


### Systemvoraussetzungen

Hier werden alle Abhängigkeiten, wie Server-Version, PHP-Version, Module etc. notiert.



## Verwendung

Eine Beschreibung zur Verwendung ist in diesem Abschnitt. Auch Code-Beispiele sind dabei sehr wichtig.

```php
<?php
  your_code_goes_here();
  f -> example();
  $xy = 'example_code';
?>
```


## Konfiguration

Dieser Abschnitt sollte beschreiben und erklären, wie die Anwendung konfiguriert werden kann:

`php generate my_example_gem:install`

Auszüge aus dem Source-Code und Screenshots sind dabei sehr hilfreich.



## Informationen

Der Aufbau der Anwendung sollte ersichtlich werden. So wird es dem Leser der Dokumentation vereinfacht die Anwendung zu überblicken.

```
anwendung/
├── css/
│   ├── styles.css
│   └── styles.min.css
├── js/
│   ├── scripts.js
│   └── scripts.min.js
└── modules/
    └── ...
```

Screenshots der Anwendung/des Projekts (diese sollten im Verzeichnis _doc/img abgelegt werden):

![Screenshot 1](http://lorempixel.com/400/300)

[Suche nach XY - Trefferliste](URL hier).

![Screenshot 2](http://lorempixel.com/g/400/300)

Jeder Screenshot benötigt eine kurze Beschreibung was darauf zu erkennen ist. Ebenso wichtig ist ein Link oder eine Linkstrecke, wie er erreichbar, bzw. nachstellbar ist.

### anwendung/modules/file.xy

Beschreibung zumindest der wichtigen Module und Dateien.

### anwendung/modules/file.xy

Beschreibung zumindest der wichtigen Module und Dateien.



## Versionierung

Unsere Releases müssen transparent sein und darum ist eine Dokumentation der Versionen wichtig. Dafür ist hier ein geeigneter Platz.

Releases werden wie folgt formatiert:

`<major>.<minor>.<patch>`

Wir haben uns dabei an die [SemVer](http://semver.org) Richtlinien gehalten:

- Die Abwärtskompatibilität wird nicht mehr gewährleistet: **neue major Version** und zurücksetzen von minor und patch
- Neue Funktionen ohne die Abwärtskompatibilität zu verletzen: **neue minor Version** und zurücksetzen von patch
- Bug fixes und kleinere Änderungen nur eine **neue patch Version**



### Known Issues

Jeder der einen Bug findet, sollte ihn bitte nicht für sich behalten, sondern ihn uns mitteilen.

[Issues List](Github Issues List URL hier).



## Autoren

* Lead-Entwickler: Vorname Name [Github Name](Github URL)
* Entwickler: Vorname Name [Github Name](Github URL)



## Copyright und Lizenz

Copyright und Informationen zur Lizenz (zb MIT) am Ende des Dokuments.