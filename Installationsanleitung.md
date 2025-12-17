# Installationsanleitung Svelte

## Node
Node.js ist notwendig, da es die Laufzeit bereitstellt, die benötigt wird, um JavaScript bzw. TypeScript außerhalb des Browsers laufen zu lassen
und npm als Packagemanager installiert.
Solltet ihr Node.js noch nicht installiert haben, dann sollte folgende Anleitung befolgt werden:

1. Downloade das passende Installationspaket der aktuellsten LTS Version unter https://nodejs.org/en/download/ . Falls du einen Mac mit einem M-Prozessor besitzt, wähle als Architektur ARM64.
Bei den meisten Windows-Rechner sollte x86 ausgewählt werden, solange es sich nicht um einen neuen Rechner mit ARM-Prozessor handelt.   
2. Installation durchklicken (Standard-Einstellungen reichen)

Prüfen, ob Node korrekt installiert ist im Terminal/Powershell:

``` powershell
node -v
npm -v
```

Die Ausgabe sollte ungerfähr so aussehen:

```
25.2.1
11.6.2
```


## Visual Studio Code
Als IDE empfehlen wir Visual Studio Code, wobei auch eine andere IDE benutzt werden kann, jedoch kein Support von unserer Seite aus geleistet werden kann.
Wenn ihr VSC benutzt, installiert bitte folgendes Plugin:
* Svelte for VS Code (von Svelte) -> Syntax-Highlighting, Autocomplete, Fehleranzeige

Download: https://code.visualstudio.com/

## Beispiel-Projekt starten

Um zu Testen, ob Svelte ordnungsgemäß auf deinem Rechner läuft, haben wir ein Test-Repository erstellt.
Klone dir dazu mit folgendem Befehl das Repo "svelte_installation_test" (dazu muss git installiert sein):

```powershell

git clone git@github.com:justinsingh024/svelte_installation_test.git

```

Wechsle in das Verzeichnis "svelte_installation_test" und führe folgende Befehle aus:

```powershell

npm i
npm run dev

```
Danach wird dir unter http://localhost:5173/ eine Willkommensseite angezeigt. Ist das der Fall, war die Installation erfolgreich.


## Support
Bei Fragen nutzt gerne das Forum, um uns zu erreichen.


