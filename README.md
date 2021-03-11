<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/SuperKohl/moonraker-MQTT-plugin">
    <img src="https://github.com/SuperKohl/moonraker-MQTT-plugin/blob/master/images/logo.PNG" alt="Logo" width="72" height="53">
  </a>

  <h3 align="center">Moonraker-MQTT-plugin</h3>

  <p align="center">
    Ein MQTT Plugin für die moonraker API
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Siehe das Wiki »</strong></a>
    <br />
    <br />
    <a href="https://github.com/SuperKohl/moonraker-MQTT-plugin/issues">Report Bug</a>
    ·
    <a href="https://github.com/SuperKohl/moonraker-MQTT-plugin/issues">Request Feature</a>
  </p>
</p>


<!-- Inhaltsverzeichnis -->
<details open="open">
  <summary>Inhaltsverzeichnis</summary>
  <ol>
    <li>
      <a href="#about-the-project">Über das Projekt</a>
      <ul>
        <li><a href="#built-with">Programmiert mit</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Installieren</a>
      <ul>
        <li><a href="#prerequisites">Voraussetzungen</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Nutzung</a></li>
    <li><a href="#roadmap">Zukünftige Änderungen</a></li>
    <li><a href="#contributing">Mitwirkende</a></li>
    <li><a href="#license">Licens</a></li>
    <li><a href="#contact">Kontakt</a></li>
    <li><a href="#acknowledgements">Danksagungen</a></li>
  </ol>
</details>



<!-- Über das Projekt -->
## about-the-project

Ein Skript / Programm zum Senden/Steuern des Druckers vor, während und nach einem Druck über das MQTT Protokoll.

### built-with

Das Plugin wurde Programmiert mit:
* [Python3](https://getbootstrap.com)
* [Jsonl](https://www.json.org/)
* [Bash]()

<!-- Installieren -->
## getting-started

### prerequisites

Vorausgesetzt wird eins der Betriebssyteme:
* [MainsailOS](https://github.com/meteyou/mainsail)
* [Fluidd](https://github.com/cadriel/fluidd)

### installation

1. Gehe in das Verzeichnis: /home/pi
   ```sh
   cd /home/pi
   ```
2. Clone das Repository
	```sh
   git clone https://github.com/SuperKohl/moonraker-MQTT-plugin.git
   ```
3. Führe das Installation-Script aus: bash ./moonraker-MQTT-plugin/scripts/install.sh
	```sh
   git clone https://github.com/SuperKohl/moonraker-MQTT-plugin.git
   ```
4. Füge in der moonraker.conf die Zeile [octoprint_compat] hinzu
	
	In MainsailOS:
	1. Gehe zu Mainsail -> Settings -> Maschine
	2. Klicke auf die Datei moonraker.conf
	3. Füge am Ende die zeile [octoprint_compat] hinzu	
	4. Klicke oben Rechts auf Save

	In Fluidd:
	1. Gehe zu  Mainsail -> Printer -> config
	2. Klicke auf die Datei moonraker.conf
	3. Füge am Ende die zeile [octoprint_compat] hinzu
	4. Klicke oben Rechts auf Save

5. Konfigurieren der moonraker_mqtt.cfg Datei

	Konfiguriere nun die moonraker_mqtt.cfg Datei. Siehe dazu das <a href="https://github.com/othneildrew/Best-README-Template"><strong>Wiki</strong></a>

<!-- Nutzung -->
## usage 


<!-- Zukünftige Änderungen -->
## roadmap


<!-- Mitwirkende -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- Licens -->
## License

Unterliegt der GNU General Public License v3.0. Siehe  `LICENSE` Für mehr Informationen.

<!-- Kontakt -->
## Contact

Malte Kollasch -  maltekollasch2003@gmail.com

Projekt Link: [https://github.com/SuperKohl/moonraker-MQTT-plugin](https://github.com/SuperKohl/moonraker-MQTT-plugin)



<!-- Danksagungen -->