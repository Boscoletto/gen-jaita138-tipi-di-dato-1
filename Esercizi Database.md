**Database 1
Gestione di una biblioteca:**


Libri: 

| Attributi | Java   | Db      |
| --------- | ------ | ------- |
| Titolo    | String | Varchar |
| Autore    | String | Varchar |
| Anno      | Int    | Date    |
| Genere    | String | Varchar |
Membri: 


| Attributi | Java   | Db      |
| --------- | ------ | ------- |
| Nome      | String | Varchar |
| Email     | String | Varchar |
| Telefono  | String | Varchar |
Prestiti:


| Attributi         | Java      | Db       |
| ----------------- | --------- | -------- |
| Data Prestito     | LocalDate | Datetime |
| Data Restituzione | LocalDate | Datetime |

**Database 2:
****Catalogo di un Ristorante**:
- Piatti

| Attributi     | Java    | Db      |
| ------------- | ------- | ------- |
| Nome          | String  | Varchar |
| Prezzo        | Float   | Decimal |
| Disponibilità | Boolean | Bit     |
| Descrizione   | String  | Varchar |


- Ingredienti


| Attributi | Java   | Db      |
| --------- | ------ | ------- |
| Nome      | String | Varchar |
| Quantità  | Float  | Decimal |


- Clienti



| Attributi | Java   | Db      |
| --------- | ------ | ------- |
| Nome      | String | Varchar |
| Email     | String | Varchar |
| Indirizzo | String | Varchar |
| Cellulare | String | Varchar |

**Database 3:
**Catalogo di un Negozio di Fiori**: 

- Fiori

| Attributi | Java   | Db      |
| --------- | ------ | ------- |
| Nome      | String | Varchar |
| Colore    | String | Varchar |
| Prezzo    | Short  | Decimal |
| Scadenza  | Float  | Date    |


- Fornitori

| Attributi | Java   | Db      |
| --------- | ------ | ------- |
| Telefono  | String | Varchar |
| Email     | String | Varchar |
| Indirizzo | String | Varchar |
| Azienda   | String | Varchar |


- Clienti

| Attributi     | Java      | Db       |
| ------------- | --------- | -------- |
| Nome          | String    | Varchar  |
| Telefono      | String    | Varchar  |
| Mail          | String    | Varchar  |
| Data reg.sito | LocalDate | Datetime |



