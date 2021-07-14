Guida registrazione programma "Raspberry":
Passo 1: Seguendo le slide ci siamo registrati e abbiamo scaricato i programmi Github e Github desktop;
Passo 2: Abbiamo creato la prima repository andando sul sito Github, poi siamo andati su code che poi ci ha portato sul programma github desktop, dopo di chè abbiamo cliccato su fetch origin e pullorigin, in seguito siamo andati su documenti e abbiamo aperto il ducumento .MD (file di testo) e ognuno ha aggiunto il proprio nominativo e la classe. Siamo ritoranti su github desktop abbiamo aggiunto la nuova modifica e poi premuto commit.
Passo 3: Abbiamo inserito la scheda (Rapsberry Pi Zero W)e andando su but creiamo un nuovo file chiamato "ssh" senza estensione;
Passo 4: Abbiamo collegato la scheda alla rete wi fi creiamo un file  “wpa_supplicant.conf”, in seguito aprire il file con il blocco note e abbiamo inserito il codice che è scritto sul pdf e salvato; 
Passo 5: Abbiamo scaricato il programma chiamato puTTy per configurare la scheda, dopo abbiamo inserito raspberrypi.local nell' host name, per vedere se la raspberry si è connessa a internet dobbiamo visualizzare se all'hotspot del cellulare compare la scheda, infine per collegare PuTTy alla raspberry abbiamo inserito l'indirizzo IP;
Passo 6: Quando apriamo il programma PuTTy, abbiamo visto che si è aperta una schermata nera in cui abbiamo inserito username e password (trovati nel pdf), e nel terminale abbiamo scritto "clear" per pulire la schermata;
Passo 7: Nel terminale digitiamo "sudo raspi-confing" e "VNC" per mettere lo schermo da remoto, digitiamo "sudo reboot" per riavviare la raspberry;
Passo 8: Scarichiamo il programma "RealVNC Viewer", inseriamo l'indirizzo Ip e inseriamo nuovamente usurname e password nel nuovo programma per accedere;

Guida registrazione programma "Esp32":
Passo 1: Iniziamo con l'installare il programma Arduino IDE.
Passo 2: Abbiamo seguito un tutorial per installare la libreria che serve ad utilizzare Esp32 versione 1.06; 
Passo 3: Iniziamo scrivendo il nostro primo codice e lo carichiamo sull'esp32 e vediamo che il codice funziona;
Passo 4: per utilizzare il sensore di umidità abbiamo installato due nuove librerie, "DHT sensor library" e "Adafruit Unifield Sensor";
Passo 5: Dopo aver installato le librerie riavviamo Arduino;
Passo 6: Iniziamo ad assemblare Arduino 