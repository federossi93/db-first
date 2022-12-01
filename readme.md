# Struttura tabella dati

<!--
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario
-->

id: | BIGINT AI(autoIncremento) PK(chiavePrimaria) NOTNULL UNIQUE 

nome: | VARCHAR(50) / NULL

modello: | VARCHAR(50) / NULL

anno: | YEAR  /NOTNULL

portiere: | CHAR(5) /NULL

kilometri_percorsi: | MEDIUMINT  / NULL

tipo_di_carburante: | VARCHAR(30) / NULL

tipo_di_motore: | VARCHAR(50)  /NOTNULL

prezzo: | DECIMAL(12,2)  / NULL






