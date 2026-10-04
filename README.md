# Pro54 VST3 Build Kit

Dieses kleine Repository baut den **offiziellen Cmajor Pro54** als privaten
**Windows x64 VST3**.

Es enthält **keinen kopierten Pro54-Quellcode**. Die GitHub Action holt beim
Build den offiziellen Cmajor-Quellstand und erzeugt daraus über den offiziellen
Cmajor-JUCE-Exporter ein VST3.

## Ziel

- Windows x64
- VST3
- Release Build
- originale Pro54-Patch-Struktur und GUI
- keine Änderung am 125A PluginScaler

## Benutzung ohne Terminal

1. Neues privates GitHub-Repository anlegen.
2. Den Inhalt dieses ZIPs in das Repository hochladen.
3. GitHub Actions öffnen.
4. `Build Pro54 VST3 Windows` ausführen.
5. Nach erfolgreichem Lauf das Artifact `Pro54-VST3-Windows-x64` herunterladen.
6. Den kompletten Ordner `Pro54.vst3` nach
   `C:\Program Files\Common Files\VST3\` kopieren.
7. Studio One neu scannen lassen.

Die Action läuft auch automatisch nach einem Push auf `main`.

## Quellen

- Cmajor: https://github.com/cmajor-lang/cmajor
- Pro54: `examples/patches/Pro54`
- JUCE: https://github.com/juce-framework/JUCE

Cmajor/Pro54 bleiben unter den jeweiligen Lizenzbedingungen der Originalquellen.
