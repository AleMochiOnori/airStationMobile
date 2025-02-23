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

### 1. Clona il repository
```sh
git clone https://github.com/tuo-username/airstation-mobile.git
cd airstation-mobile
```

### 2. Installazione delle dipendenze
Assicurati di avere **Node.js** e **Expo** installati:
```sh
npm install -g expo-cli
npm install
```

Se stai usando **yarn**:
```sh
yarn install
```

### 3. Avvio del backend
Vai nella cartella **backendPython** e avvia il server Flask:
```sh
cd backendPython
pip install -r requirements.txt
python server.py
```

### 4. Avvio dell'app mobile
Esegui Expo per testare l'app su un dispositivo o emulatore:
```sh
npm start
```
Oppure con **yarn**:
```sh
yarn start
```

### 5. Avvio su Web
Esegui Expo per testare l'app su web:
```sh
npm run web
```
Oppure con **yarn**:
```sh
yarn run web
```
Scansiona il codice QR con l'app **Expo Go** (disponibile su iOS/Android) oppure esegui su un emulatore.

## Build dell'Applicazione
Se vuoi creare un'APK o un'app iOS:

### Android
```sh
expo build:android
```

### iOS (Mac richiesto)
```sh
expo build:ios
```

Per le build con **EAS Build**:
```sh
eas build -p android --profile production
```

