# 🔐 Lecteur RFID ESP32 + PN532 pour Home Assistant

Projet de lecteur RFID/NFC basé sur ESP32 + PN532, intégré à Home Assistant via ESPHome.

---

## 📸 Photos du projet

### Lecteur RFID monté
![Lecteur RFID](images/lecteur_rfid.jpg)

### Support imprimé
![Support 1](images/support_lecteur_rfid.jpg)
![Support 2](images/support_lecteur_rfid_2.jpg)

---

## ✨ Fonctions principales

- Lecture de badges RFID / NFC
- LED WS2812B (1 LED RGB)
- Buzzer sonore
- Compatible Alarmo / Home Assistant

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

## 📦 Matériel

- ESP32 C3 / SuperMini
- PN532 (I2C)
- LED WS2812B
- Buzzer actif

---

## 🚀 Installation

1. Installer ESPHome
2. Flasher l’ESP32
3. Ajouter dans Home Assistant
4. Importer l’automatisation fournie

---

## 📜 Licence

Libre pour usage personnel.
