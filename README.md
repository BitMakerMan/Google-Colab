# Google-Colab
Google Colab (abbreviazione di Google Colaboratory ) è un servizio gratuito basato sul web offerto da Google che permette di eseguire codice Python direttamente nel browser, senza la necessità di installare nulla sul proprio computer. È particolarmente utilizzato per machine learning, data analysis e intelligenza artificiale grazie alla sua integrazione con librerie come TensorFlow, PyTorch, Pandas, ecc.

🧠 Cos’è esattamente?
Google Colab è una piattaforma Jupyter Notebook nel cloud , fornita gratuitamente da Google. Ti permette di creare e condividere documenti ("notebook") che possono contenere:

Codice Python
Risultati di esecuzione del codice (grafici, tabelle, output)
Testo formattato (usando Markdown)
Equazioni matematiche (con LaTeX)
Immagini e altro
🔌 Caratteristiche principali:
✅ Accesso facile:
Puoi accedere tramite il tuo account Google.
Nessuna installazione richiesta: funziona direttamente su browser (Chrome, Firefox, Safari...).
💻 Ambiente già configurato:
Include molte librerie preinstallate (NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow, ecc.)
Supporta l'uso di GPU e TPU (unità di elaborazione grafica e tensoriali) per accelerare calcoli complessi (es. deep learning), anch’esse gratuite fino a un certo limite.
📦 Spazio di archiviazione limitato:
Il file system locale dei notebook Colab è temporaneo. I file vengono cancellati quando la sessione termina.
Per salvare dati o modelli puoi collegare Google Drive o usare altri servizi cloud.
🌐 Collaborativo:
Come Google Docs, puoi condividere i notebook con altre persone e lavorare insieme in tempo reale.
🚀 Quando si usa?
Google Colab è ideale per:

Studio e insegnamento di Python e scienze dei dati
Prototipazione veloce di algoritmi di machine learning
Esecuzione di codice intensivo su GPU/TPU senza dover configurare hardware
Condivisione di risultati con visualizzazioni interattive
📁 Esempio pratico:
Un tipico notebook su Colab potrebbe contenere:

Una cella Markdown:

1 # Analisi vendite trimestrali
2 Questo notebook analizza le vendite dell'ultimo trimestre usando Pandas.

Una cella di codice:
python



1 import pandas as pd
2 df = pd.read_csv('vendite.csv')
3 print(df.head())

Un'altra cella di codice:
python

1 df.plot(kind='bar', x='Mese', y='Totale_vendite')

L'output del codice viene mostrato immediatamente sotto ogni cella.

⚠️ Limitazioni:
Tempo di esecuzione : Le sessioni gratuite durano massimo 12 ore consecutive (poi si disconnette).
Risorse limitate : La capacità di GPU/TPU non è illimitata e può essere sospesa se si supera un certo uso.
Memoria RAM : Circa 12-15 GB circa (variabile), insufficiente per dataset molto grandi.
🛠️ Link utile:
👉 https://colab.research.google.com
