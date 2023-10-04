| COLONNA               | TIPO        | ATTRIBUTI        | COMMENTI |
| --------------------- | ----------- | ---------------- | -------- |
| targa                 | VARCHAR(10) | PRIMARY KEY      |
| marca                 | VARCHAR(20) | NULL             |
| modello               | VARCHAR(50) | NOTNULL          |
| colore                | VARCHAR(15) | NULL             |
| alimentazione         | VARCHAR(3)  | NOTNULL          |
| km_percorsi           | FLOAT(9,3)  | PRIMARY KEY      |
| airbag                | TINYINT(1)  | NULL, DEFAULT(0) |
| porte                 | TINYINT(1)  | NULL UNSIGNED    |
| cilindrata            | SMALLINT    | NULL             |
| anno_immatricolazione | YEAR        | NOTNULL          |
| costo_acquisto        | MEDIUMINT   | NOTNULL          |
| prezzo_vendita        | MEDIUMINT   | NOTNULL          |
