# Elaborazione delle immagini (martedì 8:30-11:30 / Lab lunedì)
## Lezione 03/10/2023
### Introduzione
Alcuni elementi fondamentali da conoscere:
- segnale:
- informazione:
- rumore: 
- energia del segnale: energia necessaria per un segnale. Esistono segnali a bassa,media o alta energia (in genere pià la frequenza è alta, più energia è richiesta).
- potenza: energia per unità di tempo.

Grazie a questi elementi è possibile calcolatre il __SNR__.
### Operazioni ed esempi
Esempio delle operazioni che si possono eseguire sui segnali:
- acquisizione/ricezione.
- codifica/decodifica.
- compressione.
- trasmissione.
- analisi in tempo/frequenza.
- filtraggio.
- estrazione di caratteristiche.
- visualizzazione, calssificazione, sintesi (operazioni ad alto livello).

### Esempi di segnali
Alcuni tipi di segnali che verranno visti nel corso:
- segnale acustico: segnali che si trasmettono attraverso l'aria, ma in generale nei fluidi.
- segnale elettrico: richiede un mezzo trasmissivo (rame ad esempio).
- segnale elettromagnetico: si trasmette nel vuoto e genera campi magnetici.
- segnale sismico: si trasmette attraverso i solidi.
- segnale a grandezze astratte: non sono creati da un fenomeno fisico (ad esempio la variazione delle azioni e investimenti), e vengono rappresentati dall'analisi dei dati.

### Operazioni
Se si parla di acquisizione e ricezione di un sengale, il segnale esiste già, ma attraverso queste operazioni il segnale viene spostato in appositi mezzi. L'acquisizione avviene tramite dei sensori, che esegue un insieme di operazioni detta __catena di acquisizione__, da cui ottenniamo un segnale digitale (generalmente quindi andiamo da un segnale presente nel mondo esterno, in un segnale digitale appunto).

Se si vuole ad esempio calcolare la distanza di un oggetto, si disegna un triangolo, che tocca l'oggetto, e 2 punti di osservazione.

Il campionamento permette di trasformare un segnale digitale, in un segnale discreto, ovvero campionati nel tempo. Si genera __aliasing__ (sia in immagini, sia con video o audio), se il campionamento è basso.

La quantizzazione associa ad un segnale, dei valori specifici. Fa sempre perdere delle informazioni, a causa dell'errore di quantizzazione. Un segnale quantizzato non è un segnale digitale, infatti può essere continuo. Un segnale digitale, è un segnale quantizzato e campionato.



***
- SNR: Signal to Noise Ratio.
- Un immagine può essere vista come un segnale. 
- Lo spettro del segnale è composto da spettro di ampiezza e spettro di fase.
- Lo spettrogramma divide il segnale in finestre, e per ogni finestra esegue l'analisi spettrale.
- Il filtraggio è la trasformazione di un sengale da una forma ad un'altra (un esempio è il restauro).
- La catena di acquisizione è composto principalmente da _campionatura_ e ....
- I sensori non possono capire da che direzione arriva un determinato suono.
***