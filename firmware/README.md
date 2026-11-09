# Firmware

Passo 3, da fare.

- `nodo-c5/`: firmware della rete del prodotto più funzioni di test (registro eventi con tempo PPS, uscita di sincronismo, comandi da seriale), PWM a 5 canali.
- `monitor-c5/`: cattura dei pacchetti ESP-NOW, occupazione dei canali, lettura del CC2500, generatore di traffico Wi-Fi.
- `interfaccia-s3/`: interfaccia grafica (LVGL) con mappa della rete, occupazione dei canali, spettro, sincronia, batteria e GPS; registro su microSD.

Ambiente previsto: ESP-IDF.
