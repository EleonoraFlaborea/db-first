Esercizio di oggi: DB First
nome repo: db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Per la consegna, potete inserire la vostra tabella in un file markdown come vi ho fatto vedere a lezione, oppure farla su Excel, Fogli Google ecc e fare uno screen.
Non sono sicuro del fatto che possiate caricare direttamente un Excel, chiedo conferma a 
@Michele Spiller
 e 
@Marius Minia
Buon lavoro e a domani!


COLONNE | TIPO | ATTRIBUTI
--- | --- | ---
id | bigint | PRIMARY_KEY AUTO_INCREMENT
casa automobilistica | VARCHAR(20) | NOTNULL
modello | VARCHAR(20) | NOTNULL
carburante | CHAR(1) | NOTNULL DEFAULT(0)
km percorsi | SMALLINT | NOTNULL
prezzo | SMALLINT | NOTNULL
rate | SMALLINT | NOTNULL
portiere | TINYINT(1) | NOTNULL DEFAULT(0)
accessori | VARCHAR(200) | NULL
condizione | CHAR(1) | NOTNULL
cambio | CHAR(1) | NOTNULL DEFAULT(0)
garanzia | CHAR (7) | NOTNULL
immatricolazione | DATE | NULL
potenza | VARCHAR(14) | NULL
sedili | TYNINT(1) | NOTNULL DEFAULT(0)
colore | VARCHAR(10) | NOTNULL
cilindrata | VARCHAR(9) | NOTNULL
paese origine | CHAR(3) | NULL DEFAULT(ITA)
targa | CHAR(7) | UNIQUE NOTNULL





