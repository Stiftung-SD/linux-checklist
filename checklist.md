# Linux-Checkliste für Projekt Neptun Geräte

- Gerät: ____________________________________
- Distribution: ____________________________________

## Out of the Box Install Experience
- Konnte das System vom Stick Out of The Box gebootet werden?: [ ] ja    [ ] nein
- Konnte das System vom Stick Out of The Box ohne Fehler installiert werden?: [ ] ja    [ ] nein

## Out of the Box User Experience
Die folgenden Features sollten nach der Installation ohne weitere Interaktion funktionieren (sofern vorhanden):

### Power/Suspend/Hibernate

- [ ] Funktioniert suspend/resume bei Schliessen des Deckels?
- [ ] Funktioniert suspens/resume bei Drücken des Power-Knopfs?
- [ ] Sind die `intel_pstate` bzw. `amd_pstate`-Kernelmodule installiert & werden geladen?

### HID 

- [ ] Werden Tastatur-, Trackpad- und ggf. Trackpoint-Eingaben korrekt erkannt?
- [ ] Werden Trackpad-Gestures korrekt erkannt?
- [ ] Werden die Mediakeys/fn-F*-Funktionen korrekt erkannt?
- [ ] Funktioniert der Fingerabdruckleser?
- [ ] Funktioniert ggf. der Touchscreen?
    - [ ] Mit Fingereingaben?
    - [ ] Mit Stifteingaben? (Achtung: nicht alle Touchscreens unterstützen Stifte)
    - [ ] Bei Convertibles: Wird erkannt, wenn das Gerät im Tablet-Modus verwendet wird?
- [ ] Wird die Kamera erkannt und funktioniert sie?
    - [ ] Falls Gerät über elektrischen Kamera-Shutter verfügt, funktioniert dieser?

### Anzeige/Grafik

- [ ] Wird fractional scaling des GUI unterstützt?
- [ ] Wird die Hardware-Beschleunigung korrekt unterstützt?
    - [ ] Sind die `amdgpu` (AMD)- bzw. `mesa` (Intel)- oder `nvidia` (NVIDIA)-Treiber installiert?
    - [ ] Werden z.B. YouTube-Videos in Firefox korrekt beschleunigt?
- [ ] Werden verfügbare Bildschirmauflösungen korrekt erkannt?

### Audio

- [ ] Wird der Audiochip als Audiogerät erkannt?
- [ ] Funktionieren die Lautsprecher?
- [ ] Funktioniert der 3.5mm-Jack?
- [ ] Funktioniert das Mikrofon?
- [ ] Funktioniert Audio-Ausgabe über HDMI/DP/DP Alt Mode (USB-C)?

### Connectivity

- [ ] Wird der WLAN-Chip erkannt und kann er eine Verbindung aufbauen?
- [ ] Wird der Bluetooth-Chip erkannt und kann er eine Verbindung aufbauen?
- [ ] Werden die USB-Ports erkannt und erkennen sie Geräte?
- [ ] Falls vorhanden: Werden die Thunderbolt-Ports erkannt und erkennen sie Geräte?
- [ ] Funktioniert DP Alt Mode über die USB-/Thunderbolt-Ports?
- [ ] Falls vorhanden: Funktioniert der HDMI-Port?

