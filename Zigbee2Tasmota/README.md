
# Zigbee to Tasmota

Dokumentacia k projektu: https://tasmota.github.io/docs/Zigbee/

Zoznam kompatibilnych zariadeni: https://zigbee.blakadder.com/



## Instalacia

Ja som objednal tuto branu (https://templates.blakadder.com/ewelink_ZB-GW03) uz s napalenym Tasmota firmwerom.

Branu treba pripojit na wifi a nastavit MQTT server.

V TapHome sa potom importuje sablona "Tasmota - Zigbee GW". Parameter je adresa a port MQTT servera, musi byt rovnaka, ako na brane.
## Parovanie zariadeni

Sa da cele spravit cez TapHome, alebo v Tasmota FW.

Brana ma v TapHome prepinac na spustenie parovacieho rezimu "Permit Join".
Po spusteni treba zacat parovaciu proceduru v zariadeni.
Ak bolo parovanie uspesne, pocet najdenych zariadeni bude v premennej "Devices Found". Podrobnosti o najdenych zariadeniach (ID, vyrobca, typ) sa daju pozriet v servisnych nastaveniach brany alebo premennej.
Parovaci rezim sa po case sam deaktivuje.

Zariadenie sa do TapHome prida cez import prislusneho template. Parametre su MQTT a ID zariadenia z parovania.

