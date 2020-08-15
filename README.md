# RadioBOB ![flag](https://github.githubassets.com/images/icons/emoji/unicode/1f1e9-1f1ea.png)
PyQt5 Linux Mint / Ubuntu App für RadioBOB - Deutschlands Rockradio

#### Tray Radio App Deutsch

![alt text](https://github.com/Axel-Erfurt/RadioBOB/blob/master/screenshot.png)

Voraussetzungen:

- python 3.6
- PyQt5
- PyQt5 Multimedia
 - gstreamer
 
 #### Installation
 
 ```git clone https://github.com/Axel-Erfurt/RadioBOB.git```
 
 oder zip Datei herunterladen und entpacken
 
 [Download](https://github.com/Axel-Erfurt/RadioBOB/archive/master.zip)

 
#### PyQt5

PyQt5 Abhängige Pakete kann man über die Paketquellen installieren mit

```sudo apt-get install python3-pyqt5 python3-pyqt5.qtmultimedia libqt5multimedia5-plugins```

#### Gstreamer

Zur Nutzung müssen evtl. noch folgende zusätzliche Abhängigkeiten installiert werden.

```sudo apt-get install gstreamer1.0-libav```

#### Problembehebung

Bei einer Fehlermeldung wegen fehlenden Gstreamer Plugins kann der folgende Befehl helfen.

```sudo apt-get install gstreamer1.0-plugins-bad```

#### Programm starten

```python3 RadioBOB_D.py```
