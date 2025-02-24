# AirStation Mobile

AirStation Mobile è un'applicazione mobile sviluppata con **React Native** e **Flask** per visualizzare informazioni sulle compagnie aeree e sui voli in partenza.

## Funzionalità
- **Home Screen**: Mostra una lista delle compagnie aeree con un'interfaccia moderna e un'immagine di sfondo accattivante.
- **Visualizzazione Compagnie Aeree**: Elenco delle compagnie con nome e anno di fondazione.
- **Voli in Partenza**: Mostra un elenco aggiornato dei voli in partenza.
- **Navigazione tra schermate**: Collegamento tra diverse pagine tramite React Navigation.

## Tecnologie Utilizzate
- **Frontend**: React Native (Expo)
- **Backend**: Flask + PostgreSQL
- **Librerie principali**:
  - React Navigation
  - React Native Paper / Styled Components (per lo stile)
  - Flask-CORS (per la comunicazione tra backend e frontend)
  - PostgreSQL (database per la gestione dei dati)

## Installazione e Avvio del Progetto


## Prerequisiti

Prima di installare l'applicazione, assicurati di avere i seguenti strumenti installati sul tuo sistema:

- **Node.js e npm**: Scaricabili da [https://nodejs.org/](https://nodejs.org/)
- **Git**: Disponibile su [https://git-scm.com/](https://git-scm.com/)

## Installazione

Segui questi passaggi per installare e avviare l'applicazione:

1. **Clona il repository:**
   ```bash
   git clone https://github.com/AleMochiOnori/airStationMobile.git
   ```
   Questo creerà una cartella `airStationMobile` con il codice sorgente.

2. **Accedi alla directory del progetto:**
   ```bash
   cd airStationMobile
   ```

3. **Installa le dipendenze:**
   ```bash
   npm install
   ```
   Questo comando installerà tutte le dipendenze necessarie elencate nel `package.json`.

4. **Avvia l'applicazione:**
   ```bash
   npm start
   ```
   Questo comando avvierà l'applicazione.


## Configurare il Backend (Python + Flask)

### Crea un ambiente virtuale (consigliato):
```bash
python -m venv venv
```

### Attiva l'ambiente virtuale:

- **Su Windows:**
  ```bash
  venv\Scripts\activate
  ```
- **Su macOS/Linux:**
  ```bash
  source venv/bin/activate
  ```

### Installa le dipendenze Python:
```bash
pip install -r requirements.txt
```

### Configura il database PostgreSQL:

1. Crea un database chiamato `Voli` su PostgreSQL.
2. Modifica il file di configurazione del backend (es. `config.py` o `.env`) per inserire le credenziali del database:
   ```plaintext
   DB_HOST=localhost
   DB_NAME=Voli
   DB_USER=tuo_username
   DB_PASSWORD=tuo_password
   DB_PORT=5432
   ```

### Avvia il backend Flask:
```bash
python3 server.py
```

Il backend sarà disponibile all'indirizzo: [http://localhost:8080](http://localhost:8080).

   Questo comando avvierà l'applicazione.

