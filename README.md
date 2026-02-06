# 🎸 Guitar Omega Station

**La Workstation Definitiva per la Teoria della Chitarra.**
*Nessun framework, nessuna dipendenza pesante, pura potenza HTML, CSS e JavaScript.*

[**🚀 PROVALO ORA (LIVE DEMO)**](https://savetave.github.io/Harmonica-Omega/))
## ⚡ Descrizione
**Guitar Omega Station** è una Single-Page Application (SPA) ultra-leggera progettata per chitarristi, compositori e studenti di teoria musicale.
A differenza dei software tradizionali, questa applicazione visualizza scale, modi e accordi su una tastiera virtuale a 24 tasti in tempo reale, completa di un motore audio sintetizzato e strumenti di analisi teorica avanzata.

Il progetto è contenuto in **un singolo file HTML**, rendendolo perfetto per l'uso offline su qualsiasi dispositivo (PC, Tablet, Samsung DeX, Smartphone).

## ✨ Funzionalità Principali

### 🧠 Teoria & Visualizzazione
* **Database Scale Massiccio:** Include tutti i 7 Modi Greci, Pentatoniche (Maggiori/Minori), Blues, Bebop, Modi della Minore Melodica (Lidia Dominante, Superlocria/Alterata) e scale Esotiche (Rumena, Hirajoshi, Ungherese).
* **Motore CAGED:** Visualizza dinamicamente le 5 forme standard (box) mappate su qualsiasi tonalità, con logica "Smart Box" corretta.
* **Armonizzazione Automatica:** Calcola istantaneamente l'armonizzazione a 4 voci (Accordi di Settima) per qualsiasi scala selezionata.
* **Intervalli Intelligenti:** Mostra i gradi (R, b3, #4, ecc.) direttamente sulla tastiera.

### 📚 Prontuario Accordi (Encyclopedia)
* **Dizionario Interattivo:** Seleziona una tonica e un tipo di accordo per vedere tutte le possibili diteggiature.
* **Voicings Estesi:** Include Triadi, Power Chords, 7th, 9th, 11th, 13th, Hendrix Chord (7#9), Sus2/4 e Shell Voicings per il Jazz.
* **Visualizzazione Multi-Shape:** Mostra molteplici varianti e rivolti lungo tutto il manico.

### 🔊 Motore Audio (No MP3)
* **Web Audio API Synth:** Utilizza un sintetizzatore personalizzato basato su oscillatori (onde Sawtooth/Triangle con filtri LowPass) per simulare il timbro della chitarra senza dover caricare pesanti file audio esterni.
* **Playback Polifonico:** Ascolta scale e arpeggi suonati in sequenza con timing preciso e privo di latenza.

## 🛠️ Stack Tecnologico
* **Core:** Vanilla JavaScript (ES6+)
* **Audio:** Native Web Audio API (compatibile con tutti i browser moderni)
* **Grafica:** SVG per i diagrammi accordali + CSS Grid per la tastiera dinamica
* **Stile:** Interfaccia "Cyberpunk/Dark" realizzata con CSS Variables

## 🚀 Come Usarlo
### Online
Visita il link GitHub Pages (vedi sopra).

### Offline (Locale)
1.  Scarica il file `index.html` da questo repository.
2.  Aprilo con qualsiasi browser moderno (Chrome, Edge, Firefox, Safari).
3.  Non è richiesta alcuna connessione internet né installazione di server.

## 🤝 Contribuire
Sentiti libero di fare un fork di questo progetto! Puoi aggiungere le tue scale preferite, accordature alternative o migliorare il motore audio.

## 📜 Licenza
MIT License - Libero di usare, modificare e distribuire.
