# Auto messe in vendita da Concessionario 

| FIELD            | TYPE           | ATTRIBUTES             |
| --               |:---:           |---:                    |
| id               |INT             |AUTO_INCREMENTO UNIQUE  |
| marca            |VARCHAR(20)     |NOT NULL                |
| modello          |VARCHAR(20)     |NOT NULL                |
| immatricolazione |YEAR            |NOT NULL                |
| km               |MEDIUMINT       |NOT NULL, UNSIGNED      |
| colore           |VARCHAR(20)     |NULL                    |
| posti            |TINYINT         |NULL, UNSIGNED          |
| porte            |TINYINT         |NOT NULL, UNSIGNED      |
| alimentazione    |VARCHAR(10)     |NULL                    |
| targa            |CHAR(7)         |NOT NULL                |
| cilindrata       |MEDIUMINT       |NOT NULL, UNSIGNED      |
| cavalli          |SMALLINT        |NULL, UNSIGNED          |
| telaio           |CHAR(17)        |NOT NULL                |
| condizione       |TEXT            |NULL                    |
| prezzo           |DOUBLE(12,2)    |NOT NULL, UNSIGNED      |