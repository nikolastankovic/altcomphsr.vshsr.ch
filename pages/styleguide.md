---
title: Styleguide
---

Tipps, Tricks und einen Leitfaden, damit alle vom Gleichen reden.

Unser Grundsatz: Kurz und knackig, aber nichts verheimlichen. *Users first*!

## Beispiele / Konfigurationen

Es war einmal eine Studentin, die hiess ```Maria Muster```. Maria war während <del>dem Studium</del> den Vorlesungen fleissig und hat viele Dokumentationen mit dem Benutzernamen ```mmuster```, der E-Mail-Adresse ```maria.muster@hsr.ch``` und Marias Passwort, ```GeHeim007```, erstellt.

### Shell
Auf ihrem Computer hat Maria ein tolles Unixoid mit dem *lokalen* Benutzernamen ```maria``` installiert. Eine **root-Shell** sieht immer folgendermassen aus:

```bash
$# whoami
root
```

und eine **normale Shell** so:

```bash
$ whoami
maria
```

### Kurzum

Bezeichnung    | Bedeutung
-------------- |-----------
Name           | ```Maria Muster```
HSR-Benutzer   | ```mmuster```
E-Mail-Adresse | ```maria.muster@hsr.ch```
Passwort       | ```GeHeim007```
Shell normal   | ```$```
Shell root     | ```$#```
User lokal     | ```maria```


## Seitenhierarchie


 URL      | Bedeutung    | Beispiele
 -------- |------------- | ----------
 ```/SEITE```   | Chefseiten | Startseite, Vereinsstatuten etc.
 ```/hsr/NAME``` | Umgebung an der HSR | WLAN, Drucken
 ```/app/NAME``` | HSR-Programmkonfiguration | Thunderbird, eclipse

### Dokumentationen Umgebung an der HSR

In diese Kategorie fallen grundsätzliche, programmunabhängige **technische Angaben**.

Zudem wird jeweils die von uns empfohlene, **einfachste Lösung mit Ubuntu** von der Programmkonfiguration eingebunden. Diese sollte Anfängergerecht sein (d.h. für Benutzer mit einem Fensterplatz).


### HSR-Spezifische Programm- oder Systemkonfiguration

Hier werden **HSR-Konfigurationen für bestimmte Programme** abgelegt, sowie Schritt-für-Schritt Anleitungen für Anfänger hinterlegt.

### Weiteres

Falls deine Dokumentation hier nirgendwo reinpassen sollte oder du noch Fragen hast, mach doch bitte ein [GitHub-Issue](https://github.com/altcomphsr/altcomphsr.vshsr.ch/issues/new) auf, damit wir eine saubere Lösung finden.