# Strumenti e piattaforme

## MCU / SBC / embedded

| Famiglia | Uso tipico |
|---|---|
| **Arduino-class** (anche Mega / ATmega) | Prototipi LV, sensori, automazioni semplici, multi-modulo |
| **ESP-class** (es. NodeMCU / ESP8266) | Interfaccia a elettronica LV, linee digitali, flash sketch, UI web locale |
| **SBC classe Raspberry Pi** | Gateway/nodo in stack di monitoraggio (MCU + sensori + rete) |
| **Breadboard / millefori / PCB** | Prove, saldatura, toner-transfer / incisione, poi eventuali schede industriali |

## Laboratorio / officina leggera

- **Multimetro** — tensione, polarità, continuità, isolamento sottosistemi
- **Saldatura / dissaldatura a stagno** — prototipi e modifiche
- **Calibro / micrometro** — controlli dimensionali in contesto CNC
- **Utensili di officina** — trapano a colonna, fresa/tornio manuali di supporto
- **Saldatura a filo animato (FCAW / MIG no-gas)** — piccoli manufatti **non** strutturali (non certificata)

## CAD / CAM / grafica tecnica

| Strumento | Note |
|---|---|
| **Fusion 360** (CAD + Manufacture) | Flusso più recente: geometria, grezzo, utensile, simulazione |
| **SolidWorks**, **Rhinoceros** | Esperienza storica (non il daily driver attuale) |
| **Cura** | Slicing stampa 3D |
| **Fritzing / EAGLE** | Schemi e prove PCB in contesti storici |
| **Illustrator / Photoshop** | Grafica / prestampa (background, non il core attuale) |

## Stampa 3D / CNC

- **Stampa 3D FDM** — involucri, adattatori, prove funzionali
- **Router CNC 3 assi da banco** — legno/pannello, staffaggio, piccoli lotti, diagnosi errori CAD/CAM
- **CNC industriale (tornio / 3 assi)** — esperienza passata come operatore su programmi già predisposti (**non** programmazione industriale autonoma attuale)
- Formazione **Fanuc / ISO** — da riattivare e verificare prima di claim “pronto”

## Software legato al fisico

- Flash e test sketch su MCU ESP-class
- Piccole UI web locali su prototipo
- Commissioning delimitato di sistemi locali AI-assisted (setup + acceptance test — **non** cybersecurity)
