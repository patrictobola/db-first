# Auto usate in vendita

| Colonna            | Tipo dato   | Attributi                                  |
| ------------------ | ----------- | ------------------------------------------ |
| id                 | BIGINT      | PRIMARY_KEY NOT_NULL UNIQUE AUTO_INCREMENT |
| casa_produttrice   | VARCHAR(30) | NOT_NULL                                   |
| modello            | VARCHAR(30) | NOT_NULL                                   |
| anno_fabbricazione | YEAR        | NULL                                       |
| cilindrata         | SMALLINT    | NULL                                       |
| cavalli            | SMALLINT    | NULL                                       |
| km                 | MEDIUMINT   | NULL                                       |
| cambio             | VARCHAR(15) | NULL                                       |
| porte              | VARCHAR(1)  | NULL                                       |
| carburante         | VARCHAR(15) | NOT_NULL                                   |
| numero_proprietari | VARCHAR(2)  | NULL                                       |
| costo              | MEDIUMINT   | NOT_NULL                                   |
| finanziabile       | VARCHAR(2)  | NULL                                       |
| condizione         | VARCHAR(15) | NOT_NULL                                   |
| descrizione        | TEXT        | NULL                                       |
| disponibilità      | VARCHAR(10) | NULL                                       |
| colore             | VARCHAR(15) | NOT_NULL                                   |
| garanzia_casa      | VARCHAR(10) | NULL                                       |
