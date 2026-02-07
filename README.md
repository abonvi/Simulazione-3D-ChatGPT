# Simulazione-3D-ChatGPT

Simulazione 3D interattiva del ciclo di un motore 4 cilindri in linea (ispirato al Fiat FIRE), realizzata in un unico file HTML autocontenuto con Three.js.

## Contenuto
- **Modellazione procedurale** di basamento, albero a gomiti, pistoni, bielle e valvole.
- **Cinematica realistica** con formula esatta del pistone e sincronizzazione dei componenti.
- **Simulazione di accensione** con flash al PMS di espansione e ordine di accensione 1-3-4-2.
- **Controlli interattivi**: START/STOP, slider RPM, OrbitControls.
- **HUD** per la fase di ciascun cilindro (Aspirazione, Compressione, Espansione, Scarico).

## Avvio rapido
Avvia un server locale e apri il file `index.html`.

```bash
python -m http.server 8000
```

Poi visita: `http://127.0.0.1:8000/index.html`.

## Requisiti
- Browser moderno con supporto WebGL e moduli ES.

## Struttura
- `index.html`: simulazione completa autocontenuta.

## Licenza
Progetto dimostrativo a scopo educativo.
