# Android

## Android Stack

- System Apps

- Java API Framework

- Android Runtime

- C/C++ native lib

- HAL (Astrazione hardware)

- Linux Kernel

## Chain

Viene utilizzata la **Dalvik Virtual Machine** che è uno step intermedio nella chain. 

![](C:\Users\Samu\AppData\Roaming\marktext\images\2023-03-06-12-14-47-image.png)

Dalvik è ottimizzata per macchine con  memoria ridotta. Ogni applicazione android ha un suo contesto. 

La VM è stata sostituita da **ART**.

ART è basata su tecnologia Ahead of Time, e  non JIT come Dalvik.

-> migliore risparmio energetico ma aumena anche il consumo di spazio sulla memoria del dispositivo.



## Riassumendo

- Dispositivo Hardware - android è agnostico rispetto al processore, ma sfrutta funzioni specifiche per la sicurezza

- Sistema Operativo Android - basato su kernel linux

- Android Application Runtime - scritte in Java ed eseguite nelle Dalvik VM. Molte ora sono native. Vengono eseguite in sandboxes. 

## Tipologie di applicazioni

- Classica

- Web-based

- Integrazione con terze parti (es. bot telegram)



- Nativo

- Multi-Piattaforma

## Build

![](C:\Users\Samu\AppData\Roaming\marktext\images\2023-03-06-12-47-58-image.png)

![](C:\Users\Samu\AppData\Roaming\marktext\images\2023-03-06-12-48-35-image.png)

La firma identifica l'autore. Esiste una debug mode.

## Manifest

Identifica tutte le caratteristiche di una applicazione in `manifest.xml`. È un file pubblico. 

## Processi

- foreground - Activity/schermata

- visibili - potrebero avere ancora funzionalità per l'utente

- service - background

- cached - non servono al momento
