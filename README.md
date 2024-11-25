# Workshop über Jupyter-Notebooks am Fachschaftstag Mathematik vom 03.12.2024 (Kanton Bern)

## Installation und Verwendung (auf Windows)

### Installation von Python und Git

Auf Deinem System muss die Programmiersprache Python und die Versionsverwaltungssoftware Git installiert sein. Im Folgenden bezeichnet ```<path-to-python-folder>``` den Pfad zum Ordner, in welchem die Datei ```python.exe``` auf Deinem System abgelegt ist.

Füge ```<path-to-python-folder>\python.exe``` und ```<path-to-python-folder>\Scripts``` zur Umgebungsvariable ```PATH``` hinzu.

Für die Installation von Python 3.12 siehe hier: [Download Python 3.12](https://www.python.org/downloads/release/python-3127/).

Für die Installation von Git siehe hier: [Download Git](https://git-scm.com/downloads). 

### Klonen dieses Repositories
Im Folgenden wird mit ```<path-to-dev-folder>``` der Pfad zum Ordner, in welchem Du dieses Repository speicherst bezeichnet.
* Öffne ein Kommandozeilenwerkzeug, z.B. mit ```cmd```
* Wechsele mit ```cd <path-to-dev-folder>``` in den Entwicklungsordner
* Klone mit ```git clone https://github.com/jlieberherr/jupyter-ws-fs-tag-20241203.git``` dieses Repository

### Installation von Jupyter
#### Variante 1 (globale Installation)
* Öffne ein Kommandozeilenwerkzeug, z.B. mit ```cmd```
* Installiere Jupyter mit ```pip install juypterlab```

#### Variante 2 (innerhalb einer virtuellen Umgebung)
* Öffne ein Kommandozeilenwerkzeug, z.B. mit ```cmd```
* Wechsele mit ```cd <path-to-dev-folder>\jupyter-ws-fs-tag-20241203``` in den Entwicklungsordner
* Erzeuge mit ```"<path-to-python-folder>\python.exe"" -m venv venv_jupyter``` eine virtuelle Umgebung
* Aktiviere die virtuelle Umgebung mit ```venv_jupyter\Scripts\activate```
* Installiere Jupyter mit ```pip install jupyterlab``` innerhalb der virtuellen Umgebung

## Starten von Jupyter
* Öffne ein Kommandozeilenwerkzeug, z.B. mit ```cmd```
* Wechsele mit ```cd <path-to-dev-folder>\jupyter-ws-fs-tag-20241203``` in den Entwicklungsordner
* Falls oben Variante 2 gewählt: aktiviere mit ```venv_jupyter\Scripts\activate``` die virtuelle Umgebung
* Starte Jupyter mit ```jupyter lab```.

## Verwenden von Jupyter ohne lokale Installation
Es gibt mehrere Möglichkeiten, Jupyter im Netz ohne lokale Installation zu verwenden:
* [Google Colab](https://colab.google/) (benötigt eine Anmeldung bei Google)
* [Binder](https://mybinder.org/) (benötigt ein Github-Repository)

## Beispiele für die Verwendung von Jupyter im Unterricht

