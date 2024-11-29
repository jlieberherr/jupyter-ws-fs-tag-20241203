# Workshop über Jupyter-Notebooks am Fachschaftstag Mathematik vom 03.12.2024 (Kanton Bern)

## Installation (auf Windows)

### Installation von Python und Git

Auf Deinem System muss die Programmiersprache Python und die Versionsverwaltungssoftware Git installiert sein. Im Folgenden bezeichnet ```<path-to-python-folder>``` den Pfad zum Ordner, in welchem die Datei ```python.exe``` auf Deinem System abgelegt ist.

Füge ```<path-to-python-folder>\python.exe``` und ```<path-to-python-folder>\Scripts``` zur Umgebungsvariable ```PATH``` hinzu.

Für die Installation von Python 3.12 siehe hier: [Download Python 3.12](https://www.python.org/downloads/release/python-3127/).

Für die Installation von Git siehe hier: [Download Git](https://git-scm.com/downloads). 

### Klonen dieses Repositories
Im Folgenden wird mit ```<path-to-dev-folder>``` der Pfad zum Ordner, in welchem Du dieses Repository ablegst bezeichnet.
* Öffne ein Kommandozeilenwerkzeug, z.B. mit ```cmd```
* Wechsele mit ```cd <path-to-dev-folder>``` in den Entwicklungsordner
* Klone mit ```git clone https://github.com/jlieberherr/jupyter-ws-fs-tag-20241203.git``` dieses Repository

### Installieren der Bibliotheken
* Öffne ein Kommandozeilenwerkzeug, z.B. mit ```cmd```
* Wechsele mit ```cd <path-to-dev-folder>\jupyter-ws-fs-tag-20241203``` in den Entwicklungsordner
* Erzeuge mit ```"<path-to-python-folder>\python.exe"" -m venv venv_jupyter``` eine virtuelle Umgebung
* Aktiviere die virtuelle Umgebung mit ```venv_jupyter\Scripts\activate```
* Installiere Jupyter mit ```pip install requirements.txt``` die Bibliotheken, insbesondere Jupyter, innerhalb der virtuellen Umgebung

## Starten von Jupyter
* Öffne ein Kommandozeilenwerkzeug, z.B. mit ```cmd```
* Wechsele mit ```cd <path-to-dev-folder>\jupyter-ws-fs-tag-20241203``` in den Entwicklungsordner
* Aktiviere mit ```venv_jupyter\Scripts\activate``` die virtuelle Umgebung
* Starte Jupyter mit ```jupyter lab```
* Hinweis: Zellen in Jupyter Notebooks werden mit ```Shift + Enter``` ausgeführt

## Verwenden von Jupyter ohne lokale Installation
Es gibt mehrere Möglichkeiten, Jupyter im Netz ohne lokale Installation zu verwenden:
* [Google Colab](https://colab.google/) (benötigt eine Anmeldung bei Google).
* [Binder](https://mybinder.org/) (benötigt ein Github-Repository)

## Beispiele für die Verwendung von Jupyter im Unterricht
* Beispiel 1 (Wahrscheinlichkeitsrechnung):
  * In diesem Repository: [wuerfeln.ipynb](/wuerfeln.ipynb)
  * Auf Google Colab: TODO
* Beispiel 2 (Primzahlen):
  * In diesem Repository: [primzahlen.ipynb](/primzahlen.ipynb)
  * Auf Google Colab: TODO

