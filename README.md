# 🌙 Moon Today - EME Tracker

An essential, clean, and no-frills Android app specifically designed for amateur radio operators working in **EME (Earth-Moon-Earth)**.

## 📡 The Problem
Standard astronomy apps on the stores are cluttered with star maps, heavy 3D models, and agricultural calendars. For EME traffic, this data is often useless and distracting. When you're at the radio station powering up the dish motors, you need a real "dashboard" that tells you exactly and at a glance: *Where is the moon? How far is it? Is it a good time to operate?*

**Moon Today** was created precisely for this: open the app and get the raw data, calculated in real-time for your exact topocentric location.

## ✨ Main Features
*   **Topocentric Positioning:** Automatic GPS reading (Latitude and Longitude) from your device for perfect calculations based on your QTH.
*   **Real-Time Data:** Continuous calculation (updated every second) of **Azimuth** and **Elevation**.
*   **Distance Tracking:** Distance monitoring in km (Perigee/Apogee) with a convenient visual bar, crucial for estimating spatial degradation.
*   **Intuitive Daily Graph:** Arch drawing of today's lunar trajectory with an instant readout of the **MAX EL** (Maximum Elevation).
*   **Precise Times:** Calculation of Moonrise, Transit (Peak), and Moonset.
*   **"Field-Ready" Interface:** Developed with a modern, high-contrast UI, designed to be easily readable outdoors or while your hands are busy on the rotor controls.

## 📸 Screenshots

**73 de IK1APW** 🌕📡
<img width="540" height="1200" alt="Foto 1" src="https://github.com/user-attachments/assets/8e1c0215-c1e2-4c13-97e9-edd548b7a5f4" />

## 🛠️ Tech Stack
The app was developed entirely in **Kotlin** using the latest Android development best practices:
*   **User Interface:** Jetpack Compose.
*   **Architecture:** MVVM (Model-View-ViewModel) utilizing `StateFlow` and `Coroutines` for smooth and asynchronous updates.
*   **Astronomical Engine:** [commons-suncalc](https://shredzone.org/maven/commons-suncalc/) by Richard "shred" Z. for high-precision ephemeris calculations.
*   **GPS:** Google Play Services Location API (`FusedLocationProviderClient`).
**73 de IK1APW** 🌕📡
   

## 🚀 How to Install
1. Download the `Moon-Today v1.apk` file directly to your Android smartphone.
2. Open the file and, if prompted, allow installation from "Unknown sources".
3. Enjoy the data and aim your antennas!

## 📜 License and Acknowledgments
Open-source project. Thanks to the whole EME "lunatic" community for the inspiration. We hope this app brings you excellent lunar bounces and strong signals!

______________________________________________________________________________

# 🌙 Moon Today - EME Tracker

Un'app Android essenziale, pulita e senza fronzoli, progettata specificamente per i radioamatori che operano in **EME (Earth-Moon-Earth)**.

## 📡 Il Problema
Le classiche app astronomiche sugli store sono piene di mappe stellari, modelli 3D pesanti e calendari agricoli. Per chi fa traffico EME, questi dati sono spesso inutili e distraggono. Quando sei davanti alla stazione radio e devi dare potenza ai motori della parabola, ti serve un vero e proprio "cruscotto" che ti dica esattamente e a colpo d'occhio: *Dov'è la luna? Quanto è lontana? È un buon momento per operare?*

**Moon Today** nasce proprio per questo: aprite l'app e avete i dati nudi e crudi, calcolati in tempo reale per la vostra esatta posizione topocentrica.

## ✨ Funzionalità Principali
*   **Posizionamento Topocentrico:** Lettura automatica delle coordinate GPS (Latitudine e Longitudine) del dispositivo per calcoli perfetti dal tuo QTH.
*   **Dati in Tempo Reale:** Calcolo continuo (aggiornato ogni secondo) di **Azimut** ed **Elevazione**.
*   **Tracking Distanza:** Monitoraggio della distanza in km (Perigeo/Apogeo) con una comoda barra visiva, fondamentale per stimare la degradazione spaziale.
*   **Grafico Giornaliero Intuitivo:** Disegno ad arco della traiettoria lunare odierna con l'indicazione istantanea del **MAX EL** (Elevazione Massima).
*   **Orari Precisi:** Calcolo di Moonrise (Sorgere), Transit (Transito/Picco) e Moonset (Tramonto).
*   **Interfaccia "Da Campo":** Sviluppata con UI moderna ad alto contrasto, pensata per essere letta facilmente anche all'aperto o mentre si hanno le mani sui controlli del rotore.


## 🛠️ Tecnologie Utilizzate
L'app è stata sviluppata interamente in **Kotlin** utilizzando le migliori e più recenti pratiche di sviluppo Android:
*   **Interfaccia Utente:** Jetpack Compose.
*   **Architettura:** MVVM (Model-View-ViewModel) con l'utilizzo di `StateFlow` e `Coroutines` per aggiornamenti fluidi e asincroni.
*   **Motore Astronomico:** [commons-suncalc](https://shredzone.org/maven/commons-suncalc/) di Richard "shred" Z. per il calcolo delle effemeridi ad alta precisione.
*   **GPS:** Google Play Services Location API (`FusedLocationProviderClient`).

## 🚀 Come Installare
1. Scarica il file `Moon-Today v1.apk` direttamente sul tuo smartphone Android.
2. Apri il file e, se richiesto, consenti l'installazione da "Origini sconosciute".
3. Goditi i dati e punta le antenne!

## 📜 Licenza e Ringraziamenti
Progetto open-source. Un ringraziamento a tutta la comunità dei "lunatici" EME per l'ispirazione. Speriamo che quest'app vi porti ottimi rimbalzi lunari e segnali forti!

**73 de IK1APW** 🌕📡
