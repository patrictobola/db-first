# Auto usate in vendita

| Colonna                          | Tipo dato   | Attributi                                  |
| -------------------------------- | ----------- | ------------------------------------------ |
| id                               | BIGINT      | PRIMARY_KEY NOT_NULL UNIQUE AUTO_INCREMENT |
| casa_produttrice                 | VARCHAR(30) | NOT_NULL                                   |
| modello                          | VARCHAR(30) | NOT_NULL                                   |
| anno_fabbricazione               | YEAR        | NOT_NULL                                   |
| cilindrata                       | SMALLINT    | NULL                                       |
| cavalli                          | SMALLINT    | NULL                                       |
| km                               | MEDIUMINT   | NOT_NULL                                   |
| cambio                           | VARCHAR(11) | NULL                                       |
| porte                            | VARCHAR(1)  | NULL                                       |
| carburante                       | VARCHAR(15) | NOT_NULL                                   |
| numero_proprietari               | VARCHAR(2)  | NULL                                       |
| costo                            | MEDIUMINT   | NOT_NULL                                   |
| finanziabile                     | VARCHAR(2)  | NULL                                       |
| condizione                       | VARCHAR(15) | NOT_NULL                                   |
| descrizione                      | TEXT        | NULL                                       |
| disponibilità                    | VARCHAR(10) | NOT_NULL                                   |
| colore                           | VARCHAR(15) | NULL                                       |
| garanzia_casa_produttrice        | VARCHAR(10) | NULL                                       |
| scadenza_garanzia_concessionaria | DATE        | NULL                                       |

<!-- ******************************************
Commento sotto per non rompere il layout, (vs code me lo rompe :/ )i commenti saranno in ordine dall'alto verso il basso
*********************************************** -->

<!-- Cilindrata ho messo SMALLINT perché penso debba essere un int e non una stringa. Penso che eventuali filtri di ricerca possano fare 'es auto > 2000cc'. Stessa cosa vale per cavalli e km  -->

<!-- Cambio 11 caratteri perché oltre al cambio automatico e manuale c'è quello sequenziale :) -->

<!-- Porte lo ritengo stringa per un eventuale if futuro. -->

<!-- Condizione si riferisce allo stato della macchina: incidentata, danneggiata, come nuova, km 0, ecc ecc -->
<!-- Disponibilità ho messo un range di 10 caratteri per la disponibilità, nel caso fosse in contovendita e ci sia bisogno di aspettare n giorni perché non disponibile nell'immediato. Tra l'altro attributo secondo me necessario-->

<!-- Scadenza garanzia concessinaria ho messo DATE perché di solito è 12-24-36-48 mesi e quindi penso sia giusto mettere anche il mese e il giorno -->
