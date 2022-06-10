# tesi-transformer-italiano
Questo repository contiene il codice sviluppato per la mia tesi di laurea (luglio 2022) intitolata "**Sistema di Question Answering in italiano con modelli Transformer**"
* tesi-grillo-codice-esempi-NLP-transformer.ipynb.ipynb -  contiene il codice degli esempi demo relativi ai principlai task NLP
* tesi_grillo_codice_pdfqa.ipynb - contiene il codeice dell'applicazione PdfQA un sistema di Question Answerinf in italiano che utilizza il transfer model bert-italian-finedtuned-squadv1-it-alfa scaricato da https://huggingface.co/mrm8488/bert-italian-finedtuned-squadv1-it-alfa. L'applicazione usa come domain il file pdf gola3.pdf (scaricato da https://www.istat.it/storage/rapporti-tematici/sdgs/2021/goal3.pdf) che contiene una serie di rilevazioni ed informazioni sullo stato di salute, longevità, principali malattie, eccetera relative all'Italia. PdfQA è in grado di rispondere correttamente a domande quali:
1.	Totale dei decessi nel 2020?
2.	Deceduti oltre 80 anni?
3.	Deceduti tra 65-79 anni?
4.	Individui maggiorenni con diabete?
5.	Speranza di vita?
6.	Speranza di vita per le donne?
