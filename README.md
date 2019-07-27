# QR Code Generator (for G. Maps)

Questo esempio mostra come generare un QR code contenente un link a Google Maps con i dati inseriti in un form. I dati inseriti dall'utente sono:
- Nazione
- Città
- Indirizzo
- Numero Civico

L'esempio mostra inoltre come è possibile esportare i dati inseriti dal form ed il QR code in un file pdf.
## Librerie utilizzate

Per la generazione del QR code `jquery-qrcode`([qui](https://github.com/jeromeetienne/jquery-qrcode)), per la creazione dei file pdf `jsPDF` ([qui](https://github.com/MrRio/jsPDF)) e `html2canvas`([qui](https://html2canvas.hertzen.com)) che permette di estrarre il QR code contenuto in un div della pagina web e farlo diventare un'immagine da poter inserire nel file pdf.

## Utilizzo

In una cartella qualsiasi eseguire il comando 
```
git clone https://github.com/giacomofuria/qrcode-generator.git
```
