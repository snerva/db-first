Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

Nome tab:
Auto usate

Colonne tab:

- Marca  | VARCHAR(25) | NOTNULL
- Modello | VARCHAR(30) | NOTNULL
- Versione | VARCHAR(50) | NOTNULL
- Colore | VARCHAR(20) | NOTNULL
- Prezzo | DECIMAL(6, 3) | NOTNULL
- Anno | YEAR | NOTNULL
- Km | DECIMAL(6, 3) | NOTNULL
- Cambio | VARCHAR(10) | NOTNULL       
- Optional | TEXT | NULL
- Emissione | VARCHAR(2) | NOTNULL
- Alimentazione | VARCHAR(10) | NOTNULL
- Descrizione | TEXT | NULL