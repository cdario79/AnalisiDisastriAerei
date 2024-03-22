# Creare un ambiente virtuale con Python

### Entra nella cartella di lavoro:

<code>
cd percorso/alla/tua/cartella/progetto
</code>

### Crea un nuovo ambiente virtuale

<code>
python -m venv nome_ambiente_virtuale
</code>

es.
<code>
python -m venv venv
</code>

### Attiva l'ambiente virtuale
<code>
source venv/bin/activate
</code>

### Installare le dipendenze
<code>
pip install nome_libreria
</code>

### Uscita dall'ambiente virtuale
<code>
deactivate
</code>

### Per creare un ambiente virtuale con una versione specifica di Python
<code>
python3.9 -m venv --prompt=venv /percorso/del/venv
</code>

### Salva le dipendenze
<code>
pip freeze > requirements.txt
</code>

### Installare le dipendenze dal file requirements.txt
<code>
pip install -r requirements.txt
</code>