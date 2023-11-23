# Linux-Checkliste

Die meisten Punkte sollten out of the box zutreffen, damit wir das Gerät mit gutem Gewissen als Linux-tauglich verkaufen können.

## Power/Suspend/Hibernate

- [ ] Funktioniert suspend/resume bei Schliessen des Deckels?
- [ ] Funktioniert suspens/resume bei Drücken des Power-Knopfs?
- [ ] Sind die `intel_pstate` bzw. `amd_pstate`-Kernelmodule installiert & werden geladen?

## HID 

- [ ] Werden Tastatur-, Trackpad- und ggf. Trackpoint-Eingaben korrekt erkannt?
- [ ] Werden Trackpad-Gestures korrekt erkannt?
- [ ] Werden die Mediakeys/fn-F*-Funktionen korrekt erkannt?
- [ ] Funktioniert der Fingerabdruckleser?
- [ ] Funktioniert ggf. der Touchscreen?
    - [ ] Mit Fingereingaben?
    - [ ] Mit Stifteingaben? (Achtung: nicht alle Touchscreens unterstützen Stifte)
    - [ ] Bei Convertibles: Wird erkannt, wenn das Gerät im Tablet-Modus verwendet wird?

## Anzeige/Grafik

- [ ] Wird fractional scaling des GUI unterstützt?
- [ ] Wird die Hardware-Beschleunigung korrekt unterstützt?
    - [ ] Sind die `amdgpu` (AMD)- bzw. `mesa` (Intel)- oder `nvidia` (NVIDIA)-Treiber installiert?
    - [ ] Werden z.B. YouTube-Videos in Firefox korrekt beschleunigt?
- [ ] Werden verfügbare Bildschirmauflösungen korrekt erkannt?

## Audio

- [ ] Wird der Audiochip als Audiogerät erkannt?
- [ ] Funktionieren die Lautsprecher?
- [ ] Funktioniert der 3.5mm-Jack?
- [ ] Funktioniert das Mikrofon?

## Connectivity

- [ ] Wird der WLAN-Chip erkannt und kann er eine Verbindung aufbauen?
- [ ] Wird der Bluetooth-Chip erkannt und kann er eine Verbindung aufbauen?
- [ ] Werden die USB-Ports erkannt und erkennen sie Geräte?
- [ ] Falls vorhanden: Werden die Thunderbolt-Ports erkannt und erkennen sie Geräte?
- [ ] Funktioniert DP Alt Mode über die USB-/Thunderbolt-Ports?
- [ ] Falls vorhanden: Funktioniert der HDMI-Port?
