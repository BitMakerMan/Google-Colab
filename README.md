# Google-Colab
# Cos'è Google Colab?

**Google Colaboratory**, comunemente noto come **Google Colab**, è un servizio gratuito basato sul web offerto da Google che permette di eseguire codice Python direttamente nel browser, senza la necessità di installare nulla sul proprio computer. 
È particolarmente utilizzato per machine learning, data analysis e intelligenza artificiale grazie alla sua integrazione con librerie come TensorFlow, PyTorch, Pandas, ecc.

---

## Caratteristiche principali

### ✅ Accesso facile
- Accesso tramite account Google.
- Funziona direttamente nel browser (Chrome, Firefox, Safari...).

### 💻 Ambiente già configurato
- Include molte librerie preinstallate (NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow, ecc.).
- Supporta l'uso di **GPU** e **TPU** gratuite per accelerare calcoli complessi (es. deep learning), entro certi limiti.

### 📦 Spazio di archiviazione limitato
- Il file system locale è temporaneo: i file vengono cancellati al termine della sessione.
- Per salvare dati o modelli puoi collegare **Google Drive** o altri servizi cloud.

### 🌐 Collaborativo
- Puoi condividere i notebook con altre persone e collaborare in tempo reale, simile a Google Docs.

---

## Quando si usa?

Google Colab è ideale per:

- **Studio e insegnamento** di Python e scienze dei dati  
- **Prototipazione veloce** di algoritmi di machine learning  
- **Esecuzione di codice intensivo su GPU/TPU** senza dover configurare hardware  
- **Condivisione di risultati** con visualizzazioni interattive  

---

## Esempio pratico

Un tipico notebook su Colab può includere:

### 1. Cella Markdown:
```markdown
# Analisi vendite trimestrali
Questo notebook analizza le vendite dell'ultimo trimestre usando Pandas.
```

### 2. Cella di codice:
```
import pandas as pd

df = pd.read_csv('vendite.csv')
print(df.head())
```

### 3. Altra cella di codice:
```
import matplotlib.pyplot as plt

df.plot(kind='bar', x='Mese', y='Totale_vendite')
plt.title("Vendite Trimestrali")
plt.xlabel("Mese")
plt.ylabel("Totale Vendite")
plt.show()
```
L'output del codice viene mostrato immediatamente sotto ogni cella.

---
⚠️ Limitazioni
Tempo di esecuzione : Le sessioni gratuite durano massimo 12 ore consecutive .
Risorse limitate : L'accesso a GPU/TPU può essere sospeso se si supera un certo uso.
Memoria RAM : Circa 12-15 GB , insufficiente per dataset molto grandi.
---

🔗 Link utile 👉 https://colab.research.google.com

