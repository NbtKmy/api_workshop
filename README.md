# Materialien für den Workshop "**Introducing APIs: Datenquellen entdecken und mit Python nutzen Einleitung**"


Im Ordner "notebooks" dieses Repos befinden sich die Notebooks für den Workshop. 
Wir verwenden sie vor allem im Hands-on-Teil. 

## Für OLAT-Kurs

Im Workshop wird die virtuelle Umgebung in OLAT verwendet.
Hier die Beschreibung, wie man die Umgebnung in OLAT aufbaut:

1. Wenn man die Jupyterlab-Umgebung in OLAT geöffnet hat, kann man über den Link auf das erste Notebook gelangen, die durch [nbgitpuller link generator](https://nbgitpuller.readthedocs.io/en/latest/link.html) erstellt worden ist. 
Dieser Link ist in einem Dokument "link_to_jupyter.txt" im "Materialordner" von OLAT zu finden.
Den Link kopieren und in einem beliebigen Webbrowser öffnen, wo man sich auch in OLAT angemeldet ist.

2. Dann öffnet sich das Notebook "1_intro.ipynb". In diesem Zustand sollten noch ein Paar Python-Libraries installiert werden, die in "requirements.txt" geschrieben sind. Deshalb:

- Bitte einen neuen Tab öffnen und "Terminal" anwählen
- Die folgenden Befehle in Terminal eingeben:

```
cd ~
pip install -r api_workshop/requirements.txt
```


## Durch git clone

Man kann natürlich das Repo clonen und durch "uv" die Python-Umgebung wiederherstellen.

```bash
git clone https://github.com/NbtKmy/api_workshop.git
cd api_workshop
uv sync
```


