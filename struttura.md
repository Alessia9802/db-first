<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario -->

#Concessionaria d'auto

#(Tabella) auto usate:

-Id | BIGINT - PRIMARY KEY, NOTNULL, UNIQUE, AUTO INCREMENT
-Quantità | TINYINT - NOT NULL
-Targa | VARCHAR(5) - NULL
-Modello | VARCHAR(8) - NOT NULL
-Copie_modello | TINYINT - NOT NULL
-Condizione | VARCHAR(5) - NULL
-Prezzo | DECIMALI(5,3) - NULL
-Promozione | TINYINT - NULL
-Posti | SMALLINT - NULL
-Marca | VARCHAR(10) - NULL
-Anno_di_fabbricazione | YEAR - NULL
-Alimentazione | VARCHAR(10) - NOT NULL
-Km(chilometri) | DECIMALI(6,3) - NOT NULL
-Carrozzeria | TINYINT - NULL
-Disponibilità | TINYINT - DEFAULT
-Ricambi | TINYINT - NULL
-Accessori | TINYINT - NULL
-Pneumatici | SMALLINT - NULL
-Assistenza | DATETIME - NULL
