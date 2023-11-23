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