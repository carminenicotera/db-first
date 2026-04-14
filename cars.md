| Nome colonna           | Tipo di Dato | Attributi                       |
| ---------------------- | ------------ | ------------------------------- |
| Id (PRIMARY KEY)       | INT          | NOT NULL, UNIQUE, AUTOINCREMENT |
| Marca                  | VARCHAR(50)  | NOT NULL                        |
| Modello                | VARCHAR(50)  | NOT NULL                        |
| Immatricolazione       | YEAR         | NOT NULL                        |
| Foto                   | TEXT         | NULL                            |
| Motore                 | VARCHAR(50)  | NOT NULL                        |
| Colore                 | VARCHAR(15)  | DEFAULT                         |
| Targa                  | CHAR(7)      | NOT NULL, UNIQUE                |
| Chilometraggio         | DECIMAL(9,3) | NULL                            |
| Carburante             | VARCHAR(20)  | NOT NULL                        |
| Tipo_di_cambio         | VARCHAR(20)  | NULL                            |
| Classe_di_emissioni    | VARCHAR(20)  | NULL                            |
| Precedenti_proprietari | TINYINT      | NULL                            |
| Prezzo                 | DECIMAL(9,3) | NULL                            |