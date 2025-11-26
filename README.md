# 🔐 Lecteur RFID ESP32 + PN532 pour Home Assistant

Ce projet permet de créer un lecteur RFID avec un ESP32 et un module PN532, afin de piloter une alarme dans Home Assistant.

## ✨ Fonctions

- Lecture de badges RFID / NFC
- LED de statut (WS2812B)
- Buzzer sonore
- Intégration Home Assistant via ESPHome
- Automatisation simple : un badge = activer/désactiver l’alarme

---

## 🧰 Matériel nécessaire

- ESP32 (ESP32-C3 / SuperMini)
- Module PN532 (I2C)
- LED WS2812B (1 LED)
- Buzzer actif

---

## 🔌 Câblage

| Module | ESP32 |
|--------|------|
| PN532 VCC | 3.3V |
| PN532 GND | GND |
| PN532 SDA | GPIO5 |
| PN532 SCL | GPIO6 |
| LED WS2812B DIN | GPIO2 |
| LED VCC | 5V |
| LED GND | GND |
| Buzzer + | GPIO7 |
| Buzzer - | GND |

---

## 🚀 Installation

1. Installer ESPHome
2. Flasher l’ESP32 avec le fichier YAML
3. Ajouter l’intégration dans Home Assistant
4. Importer l’automatisation

---

## 📜 Licence

Projet libre à usage personnel et communautaire.

