# es_extended-DOUBLE-JOB
### This is the es_extended v1 final with the double job function

This resource was modified by me for my FiveM server called Eureka RP (https://discord.io/eurekarp if you want to enter), it's an Italian server set in Los Angeles.

## ! WARNING !
In my server I use the b1g_notify notification system slightly modified by me with some more events and notifications that also play a sound (via Interact sound https://github.com/plunkettscott/interact-sound), so for a complete functioning of es_extended you should download this system too from my GitHub (), otherwise you can restore the standard notifications by commenting on what I have modified.

## ! Installation !
```
- Replace your es_extended with this version
- Import into your DB
- Start the resource in the server.cfg
```

## ! Utilizzo !
Ho inserito un comando che si richiama digitando ```/setjob2 [ID] [lavoro] [grado]``` per settare il secondo lavoro di un player.
Qualsiasi lavoro può essere settato come secondo lavoro ma se non è configurato non funzionerà.
Per la configurazione vi basterà andare nei file di qualsiasi vostro lavoro e cambiare le condizioni che verificano il lavoro del player da PlayerData.job a PlayerData.job2. La risorsa supporta anche il secondo stipendio sia da una società (richiede esx_society) sia normalmente, ma per avere la gestione dell'azienda come secondo lavoro dovrete creare una modifica di esx_society.
