# analisi_aziende_unicorno

Le aziende unicorno rappresentano un elenco di aziende private con un valore superiore a 1 miliardo di dollari. I dati includono il nome del paese in cui è stata fondata l'azienda, la sua valutazione attuale, i finanziamenti, il settore, i principali investitori, l'anno di fondazione e l'anno in cui ha raggiunto una valutazione di 1 miliardo di dollari.

Il set di dati contiene:

- **1.074 righe** (in cui ogni riga rappresenta un'azienda diversa);
- **10 colonne**

|Nome colonna|Tipo|Descrizione|
|---|---|---|
|Company|str|Nome azienda|
|Valuation|str|Valutazione dell'azienda in miliardi (B) di dollari|
|Date Joined|datetime|Data in cui l'azienda ha raggiunto 1 miliardo di dollari di valutazione|
|Industry|str|Settore dell'azienda|
|City|str|Città di fondazione dell'azienda|
|Country/Region|str|Paese di fondazione dell'azienda|
|Continent|str|Continente di fondazione dell'azienda|
|Year Founded|int|Anno di fondazione dell'azienda|
|Funding|str|Importo totale raccolto in tutti i round di finanziamento|
|Select Investors|str|Principali 4 società di investimento o investitori individuali (alcuni ne hanno meno di 4)|

**Fonte dei dati**: [Aziende Unicorno](https://www.kaggle.com/datasets/mysarahmadbhat/unicorn-companies)  

**Anno**: aggiornati al 2022.

## Riepilogo dell'analisi

In questa attività, scoprirò le caratteristiche del dataset e utilizzerò le visualizzazioni per analizzarlo attraverso l'analisi esplorativa (EDA).
- [Analisi EDA](EDA_Aziende_Unicorn.ipynb)

Lo scopo è quello di utilizzere queste informazioni per comprendere come e quando le aziende raggiungono questo prestigioso traguardo e per fornire raccomandazioni sui prossimi passi da compiere ad una sociaetà fittizia di di investimenti.



