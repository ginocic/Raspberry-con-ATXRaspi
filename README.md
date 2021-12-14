# Raspberry con ATXRaspi
Installazione e configurazione del modulo ATXRaspi per Raspberry.
ATXRaspi è un controller di alimentazione intelligente versatile per RaspberryPi. Consente di spegnere o riavviare il tuo Pi premendo un pulsante, senza bisogno di accedere per eseguire quei comandi tramite la console/ssh. Inoltre, interromperà completamente l'alimentazione al Pi in caso di spegnimento.
L'ultima revisione di ATXRaspi (R3) permette di configurare vari parametri funzionali e di comportamento.
È possibile utilizzare ATXRaspi con:
- pulsanti momentanei o interruttori a scatto
- con o senza led
- gestione software delle procedure di riavvio e/o spegnimento

# Requisiti
1. Raspberry con sistema operativo giá installato e configurato. Seguire la [guida](https://github.com/ginocic/Preparazione-Raspberry)
2. (Facoltativo) Installare un display oled per alcune informazioni del sistema. Seguire la [guida](https://github.com/ginocic/RaspberryPi-Display-OLED)
3. (Facoltativo) Spostare il rootfs su disco SSD e attivazione del servizio TRIM. Seguire la [guida](https://gist.github.com/ginocic/3322d84c035f09ca956418c88c8f9b43)
4. ATXRaspi. [Informazioni e guida](https://lowpowerlab.com/guide/atxraspi/?view=all) e [acquisto](https://lowpowerlab.com/shop/product/91)

# Premessa
Qui viene eseguita l'assemblaggio, installazione e configurazione del Modulo ATXRaspi con le seguenti caratteristiche:
- pulsante momentaneo con led
- spegnimento completo da software

Per ulteriori modalitá e/o caratteristiche, fare riferimento alla [guida ufficiale](https://lowpowerlab.com/guide/atxraspi/?view=all) dal sito ufficiale.

# Fase 1 - Connessione al Raspberry
