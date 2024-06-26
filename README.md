<!--
*** Official XDSN README
*** by High¢Kali, 2024
-->


🚀 **$DSN su xdsnOS**: Rivoluziona il tuo mondo digitale con $DSN, il nostro token nativo sulla rete Polygon, ora integrato in xdsnOS. Questo sistema operativo innovativo, dotato di un miner versatile, è progettato per funzionare su qualsiasi dispositivo connesso a Internet, portando la potenza del mining di criptovalute ovunque tu sia, su qualsiasi hardware, inclusi i classici Atari. 🌐

🔒 **Protezione Anti-Censura e in Tempo Reale**: xdsnOS non è solo un sistema operativo, ma una fortezza contro la censura e un baluardo contro il cyberbullismo. Con xdsnOS, vivi in un ambiente digitale dove la tua libertà è sempre protetta. 🛡️

🎓 **Hub Educativo**: xdsnOS trascende i confini dell'apprendimento. Condividiamo conoscenze e risorse preziose, aprendo le porte dell'educazione a una comunità globale. 📚

💡 **$DSN e XDSN**: Nato dalla rete Polygon, $DSN si evolve in XDSN attraverso una fork di Duino-Coin, ampliando le possibilità del mining decentralizzato e dell'innovazione blockchain. Preparati a un'esperienza di mining senza precedenti, accessibile a tutti e personalizzabile per ogni esigenza. 💻

💻 Supportato da un gran numero di piattaforme
👥 Una comunità in rapida crescita
💱 Facile da usare e scambiare
(su DUCO Exchange, JustSwap, SushiSwap)
🌎 Disponibile ovunque
🆕 Progetto completamente originale e open source
🌳 Principiante ed ecologico
💰 Conveniente e facile da estrarre
⚒️ Algoritmo: DUCO-S1
♐ Premi: supportato dal "sistema Kolka"
che aiuta a ricompensare equamente i minatori
⚡ Tempo di transazione: istantaneo
🪙 Fornitura di monete: infinita
(con combustione)
🔤 Ticker: DUCO (ᕲ)
🔢 Decimali: fino a 20
♾️ Arduino
(Uno, Nano, Mega, Due, Pro Mini, ecc.)
📶 ESP8266
(NodeMCU, Wemos, ecc.)
📶 ESP32
(ESP-WROOM, ESP32-CAM, ecc.)
🍓 Raspberry Pis
(1, 2, Zero (W/WH), 3, 4, Pico, 400)
🍊 Orange Pis
(Zero, Zero 2, PC, Plus, ecc.)
⚡ Schede Teensy 4.1 

## Getting started

### The easy way
Get started with Duino-Coin by downloading [the latest release](https://github.com/revoxhere/duino-coin/releases/latest) for your OS.<br>
Then unzip it and launch the desired program. There are no dependencies required.

If you need help, you can take a look at the official getting started guides located <a href="https://duinocoin.com/getting-started">on the official website</a>.<br>
FAQ and troubleshooting help can be found in the [Wikis](https://github.com/revoxhere/duino-coin/wiki).<br>

### The hard way

#### Linux (manual installation)

```BASH
sudo apt update
sudo apt install python3 python3-pip git python3-pil python3-pil.imagetk -y # Install dependencies
git clone https://github.com/revoxhere/duino-coin # Clone Duino-Coin repository
cd duino-coin
python3 -m pip install -r requirements.txt # Install pip dependencies
```

After doing this, you are good to go with launching the software (e.g. `python3 PC_Miner.py`).

#### Windows (manual installation)

1. Download and install [Python 3](https://www.python.org/downloads/) (make sure you add Python and Pip to your PATH)
2. Download [the Duino-Coin repository](https://github.com/revoxhere/duino-coin/archive/master.zip)
3. Extract the zip archive you've downloaded and open the folder in command prompt
4. In command prompt type `py -m pip install -r requirements.txt` to install required pip dependencies

After doing this, you are good to go with launching the software (just double click on desired `.py` files or type `py PC_Miner.py` in the command prompt).

#### Raspberry Pi (automatic installation)

```BASH
wget https://raw.githubusercontent.com/revoxhere/duino-coin/master/Tools/duco-install-rpi.sh
sudo chmod a+x duco-install-rpi.sh
./duco-install-rpi.sh
```

## DUCO, wDUCO, bscDUCO, maticDUCO & celoDUCO

Duino-Coin is a hybrid currency providing support both to centralized and decentralized ways of storing funds. Duino-Coins can be converted to wDUCO, bscDUCO or others which are the same Duino-Coins but "wrapped" (stored) on other networks as tokens. An example tutorial on using wDUCO is available in the [wDUCO wiki](https://github.com/revoxhere/duino-coin/wiki/wDUCO-tutorial). Coins can be wrapped directly from your web Wallet - click the Wrap Coins button to start.

## Development

Contributions are what make the open source community such an amazing place to be learn, inspire, and create.<br>
Any contributions you make to the Duino-Coin project are greatly appreciated.

How to help?

*   Fork the Project
*   Create your feature branch
*   Commit your changes
*   Make sure everything works as intended
*   Open a pull request

Server source code, documentation for API calls and official libraries for developing your own apps for Duino-Coin are available in the [useful tools](https://github.com/revoxhere/duino-coin/tree/useful-tools) branch.


## Version 4.0 reward goals

Captured at normal multiplier (no weekend boost)
| Device                | Hashrate            | Threads | DUCO/day |
|-----------------------|---------------------|---------|----------|
| Arduino               | 343 H/s             | 1       | 12       |
| ESP32                 | 84 kH/s (2x42 kH/s) | 2       | 10       |
| ESP32-S2/C3           | 82 kH/s             | 1       | 8        |
| ESP8266               | 66 kH/s             | 1       | 6        |
| Raspberry Pi 4 (LOW)  | 1 MH/s (no fasthash)| 4       | 6-7      |
| Raspberry Pi 4 (MED)  | 5.4 MH/s (fasthash) | 4       | 7-8      |
| Low power PCs         |                     | 4       | 4-6      |
| Medium                |                     | 4-8     | 6-10     |
| High end              |                     | 8+      | 10-12    |

<details>
  <summary><b>Other tested devices and their benchmarks</b></summary>
  
Please note the DUCO/day column has been removed since version 4.0 changed the reward system.
| Device/CPU/SBC/MCU/chip                                   | Average hashrate<br>(all threads) | Mining<br>threads | Power<br>usage |
|-----------------------------------------------------------|-----------------------------------|-------------------|----------------|
| Raspberry Pi Pico                                         | 5 kH/s                            | 1                 | 0.3 W          |
| Raspberry Pi Zero                                         | 18 kH/s                           | 1                 | 1.1 W          |
| Raspberry Pi 3 **(32bit)**                                | 440 kH/s                          | 4                 | 5.1 W          |
| Raspberry Pi 4 **(32bit)**                                | 740 kH/s                          | 4                 | 6.4 W          |
| Raspberry Pi 4 **(64bit, fasthash)**                      | 6.8 MH/s                          | 4                 | 6.4 W          |
| ODROID XU4                                                | 1.0 MH/s                          | 8                 | 5 W            |
| Atomic Pi                                                 | 690 kH/s                          | 4                 | 6 W            |
| Orange Pi Zero 2                                          | 740 kH/s                          | 4                 | 2.55 W         |
| Khadas Vim 2 Pro                                          | 1.12 MH/s                         | 8                 | 6.2 W          |
| Libre Computers Tritium H5CC                              | 480 kH/s                          | 4                 | 5 W            |
| Libre Computers Le Potato                                 | 410 kH/s                          | 4                 | 5 W            |
| Pine64 ROCK64                                             | 640 kH/s                          | 4                 | 5 W            |
| Intel Celeron G1840                                       | 1.25 MH/s                         | 2                 | 53 W           |
| Intel Core i5-2430M                                       | 1.18 MH/s                         | 4                 | 35 W           |
| Intel Core i5-3230M                                       | 1.52 MH/s                         | 4                 | 35 W           |
| Intel Core i5-5350U                                       | 1.35 MH/s                         | 4                 | 15 W           |
| Intel Core i5-7200U                                       | 1.62 MH/s                         | 4                 | 15 W           |
| Intel Core i5-8300H                                       | 3.67 MH/s                         | 8                 | 45 W           |
| Intel Core i3-4130                                        | 1.45 MH/s                         | 4                 | 54 W           |
| AMD Ryzen 5 2600                                          | 4.9 MH/s                          | 12                | 65 W           |
| AMD Ryzen R1505G **(fasthash)**                           | 8.5 MH/s                          | 4                 | 35 W           |
| Intel Core i7-11370H **(fasthash)**                       | 17.3 MH/s                         | 8                 | 35 W           |
| Realtek RTD1295                                           | 490 kH/s                          | 4                 | -              |
| Realtek RTD1295 **(fasthash)**                            | 3.89 MH/s                         | 4                 | -              |

</details>

## Community-made softwares

### Please note that these softwares are not developed by us and we do not give any guarantees that use of them will not result in an account getting banned. Treat them as a curiosity. 

  ### Other miners known to work with Duino-Coin:
  *   [Dockerized Duino-Coin Miner](https://github.com/simeononsecurity/docker-duino-coin) - A Dockerized version of the Duino-Coin Miner
  *   :point_right: [**RP2040-HAT-MINING-C**](https://github.com/Wiznet/RP2040-HAT-MINING-C) - **WIZnet RP2040** mining stack
  *   [DuinoCoinEthernetMiner](https://github.com/Pumafron/DuinoCoinEthernetMiner) - Arduino Ethernet shield Miner by Pumafron
  *   [STM8 DUCO Miner](https://github.com/BBS215/STM8_DUCO_miner) - STM8S firmware for mining DUCO by BBS215
  *   [DuinoCoinbyLabVIEW](https://github.com/ericddm/DuinoCoinbyLabVIEW) - miner for LabVIEW family by ericddm
  *   [Duino-JS](https://github.com/Hoiboy19/Duino-JS) - a JavaScript miner which you can easily implement in your site by Hoiboy19
  *   [Duinotize](https://github.com/mobilegmYT/Duinotize) - Duino website monetizer by mobilegmYT
  *   [hauchel's duco-related stuff repository](https://github.com/hauchel/duco/) - Collection of various codes for mining DUCO on other microcontrollers
  *   [duino-coin-php-miner](https://github.com/ricardofiorani/duino-coin-php-miner) Dockerized Miner in PHP by ricardofiorani
  *   [duino-coin-kodi](https://github.com/SandUhrGucker/duino-coin-kodi) - Mining addon for Kodi Media Center by SandUhrGucker
  *   [MineCryptoOnWifiRouter](https://github.com/BastelPichi/MineCryptoOnWifiRouter) - Python script to mine Duino-Coin on routers by BastelPichi
  *   [Duino-Coin_Android_Cluster Miner](https://github.com/DoctorEenot/DuinoCoin_android_cluster) - mine with less connections on multiple devices by DoctorEenot
  *   [ESPython DUCO Miner](https://github.com/fabiopolancoe/ESPython-DUCO-Miner) - MicroPython miner for ESP boards by fabiopolancoe
  *   [DUCO Miner for Nintendo 3DS](https://github.com/BunkerInnovations/duco-3ds) - Python miner for Nintendo 3DS by PhereloHD & HGEpro
  *   [Dockerized DUCO Miner](https://github.com/Alicia426/Dockerized_DUCO_Miner_minimal) - Miner in Docker by Alicia426
  *   [NodeJS-DuinoCoin-Miner](https://github.com/LDarki/NodeJS-DuinoCoin-Miner/) - simple NodeJS miner by LDarki
  *   [d-cpuminer](https://github.com/phantom32-0/d-cpuminer) - pure C miner by phantom32 & revoxhere
  *   [Go Miner](https://github.com/yippiez/go-miner) by yippiez
  *   [ducominer](https://github.com/its5Q/ducominer) by its5Q
  *   [Unofficial miners directory](https://github.com/revoxhere/duino-coin/tree/master/Unofficial%20miners)
      *   [Julia Miner](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Julia_Miner.jl) by revoxhere
      *   [Ruby Miner](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Ruby_Miner.rb) by revoxhere
      *   [Minimal Python Miner (DUCO-S1)](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Minimal_PC_Miner.py) by revoxhere
      *   [Teensy 4.1 code for Arduino IDE](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Teensy_code/Teensy_code.ino) by joaquinbvw

  ### Other tools:
  *   [Duino Miner](https://github.com/g7ltt/Duino-Miner) - Arduino Nano based DUCO miner files and documentation by g7ltt
  *   [DUINO Mining Rig](https://repalmakershop.com/pages/duino-mining-rig) - 3D files, PCB designs and instructions for creating your own Duino rig by ReP_AL
  *   [DuinoCoin-balance-Home-Assistant](https://github.com/NL647/DuinoCoin-balance-Home-Assistant) - addon for home assistant displaying your balance by NL647
  *   [ducopanel](https://github.com/ponsato/ducopanel) - a GUI app for controling your Duino-Coin miners by ponsato
  *   [Duino AVR Monitor](https://www.microsoft.com/store/apps/9NJ7HPFSR9V5) - GUI Windows App for monitoring AVR devices mining DUCO by niknak
  *   [Duino-Coin Arduino library](https://github.com/ricaun/arduino-DuinoCoin) by ricaun
  *   [DuinoCoinI2C](https://github.com/ricaun/DuinoCoinI2C) - Use ESP8266/ESP32 as a master for Arduinos by ricaun
  *   [Duino-Coin Mining Dashboard](https://lulaschkas.github.io/duco-mining-dashboard/) and troubleshooting helper by Lulaschkas
  *   [duco-miners](https://github.com/dansinclair25/duco-miners) CLI mining dashboard made by dansinclair25
  *   [Duco-Coin Symbol Icon ttf](https://github.com/SandUhrGucker/Duco-Coin-Symbol-Icon-ttf-.h) by SandUhrGucker
  *   [DUCO Monitor](https://siunus.github.io/duco-monitor/) account statistics website by siunus
  *   [Duino Stats](https://github.com/Bilaboz/duino-stats) official Discord bot by Bilaboz
  *   [DuCoWallet](https://github.com/viktor02/DuCoWallet) GUI Wallet by viktor02
  *   [Duco-widget-ios](https://github.com/naphob/duco-widget-ios) - a Duino-Coin iOS widget by Naphob 
  *   [Duino Lookup](https://axorax.github.io/duino-lookup/) by axorax

 You may also view a similar list on the [website](https://duinocoin.com/apps).


## License

Duino-Coin is mostly distributed under the MIT License. See the `LICENSE` file for more information.
Some third-party included files may have different licenses - please check their `LICENSE` statements (usually at the top of the source code files).


## Terms of service
Our terms of service is available here: <a href="https://duinocoin.com/terms">duinocoin.com/terms</a><br/>


## Privacy policy
Our privacy policy is available here: <a href="https://duinocoin.com/privacy">duinocoin.com/privacy</a><br/>

## Disclaimer
Our disclaimer is available here: <a href="https://duinocoin.com/disclaimer">duinocoin.com/disclaimer</a><br/>


## Active project maintainers

*   [@revoxhere](https://github.com/revoxhere/) - robik123.345@gmail.com (Lead Python dev, project founder)
*   [@Bilaboz](https://github.com/bilaboz/) (Lead NodeJS dev)
*   [@Tech1k](https://github.com/Tech1k/) - hello@kristiankramer.net (Lead Webmaster and DUCO Developer)
*   [@ygboucherk](https://github.com/ygboucherk) ([wDUCO](https://github.com/ygboucherk/wrapped-duino-coin-v2) dev)
<!-- *   [@connorhess](https://github.com/connorhess) (Lead Python dev, Node-S owner) -->
<!-- *   [@JoyBed](https://github.com/JoyBed) (Lead AVR dev) -->
<!-- *   [@Yennefer](https://www.instagram.com/vlegle/) (Lead social manager) -->
<!-- *   [@Lulaschkas](https://github.com/Lulaschkas) (Dev) -->
<!-- *   [@joaquinbvw](https://github.com/joaquinbvw) (AVR dev) -->

Big thanks to all the [contributors](https://github.com/revoxhere/duino-coin/graphs/contributors) that helped to develop the Duino-Coin project.
Visit [duinocoin.com/team](https://duinocoin.com/team.html) to view more information about the Duino Team.

<hr>

Established August 2019 <br>
Project Link: [https://github.com/revoxhere/duino-coin/](https://github.com/revoxhere/duino-coin/) <br>
Website Link: [https://duinocoin.com/](https://duinocoin.com/) <br>
Duino-Coin Status Page: [https://status.duinocoin.com](https://status.duinocoin.com)
