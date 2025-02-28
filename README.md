# Template per la Presentazione della Tesi - Università degli Studi di Padova

## Descrizione
Questo repository contiene un **template LaTeX** per la presentazione della tesi presso l'**Università degli Studi di Padova**, **Dipartimento di Ingegneria dell'Informazione (DEI)**. Il template segue il formato richiesto per le presentazioni accademiche e include stile, struttura e comandi personalizzati per facilitare la stesura della presentazione.

## Struttura del Repository
```
📂 progetto
 ┣ 📂 images            # Contiene le immagini utilizzate nelle slide
 ┣ 📂 codice              # Contiene eventuali script di supporto
 ┣ 📜 presentation.tex            # File LaTeX principale per la presentazione
 ┣ 📜 beamerthemePadovaDEI.sty # Tema Beamer personalizzato per il DEI
 ┣ 📜 README.md           # Questo file
 ┗ 📜 Makefile            # Script per la compilazione automatica
```

## Requisiti
Per utilizzare questo template, è necessario avere installato **TeX Live** (Linux/Mac) o **MikTeX** (Windows) con i pacchetti necessari.

### **Installazione su macOS**
Si consiglia di installare **MacTeX**, una distribuzione TeX completa per macOS. Seguire questi passaggi:

1. Scaricare l'installer di MacTeX dal [sito ufficiale](https://tug.org/mactex/).
2. Eseguire il file `.pkg` scaricato e seguire le istruzioni sullo schermo.
3. Dopo l'installazione, verificare l'installazione aprendo il Terminale e digitando:
   ```bash
   pdflatex --version
   ```
   Dovrebbe apparire la versione di `pdflatex` installata.

### **Installazione su Linux**
```bash
sudo apt update && sudo apt install -y texlive-full
```

### **Installazione su Windows**
Scaricare e installare **MikTeX** da [qui](https://miktex.org/download).

## Compilazione della Presentazione
Per compilare il file `presentation.tex`, eseguire:
```bash
pdflatex presentation.tex
```
Oppure, se si utilizza **Makefile**:
```bash
make
```

## Personalizzazione
Il file `beamerthemePadovaDEI.sty` contiene le personalizzazioni per il tema della presentazione. È possibile modificare:
- **Colori e stile delle slide**
- **Font e dimensioni del testo**
- **Struttura dei titoli e sottotitoli**

## Esempi di Slide
Di seguito sono riportati alcuni esempi di slide generate con questo template:

![Esempio Slide 1](./immagini/slide1.png)
*Figura 1: Esempio di slide introduttiva.*

![Esempio Slide 2](./immagini/slide2.png)
*Figura 2: Esempio di slide con contenuto.*

## Contributi
Se vuoi contribuire al miglioramento del template, puoi inviare una **pull request** o aprire un **issue** su GitHub.

## Licenza
Questo template è distribuito sotto licenza **MIT**.

