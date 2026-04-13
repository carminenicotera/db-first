| Nome colonna           | Tipo di Dato | Attributi                       |
| ---------------------- | ------------ | ------------------------------- |
| Id (PRIMARY KEY)       | INT          | NOT NULL, UNIQUE, AUTOINCREMENT |
| Marca                  | VARCHAR(50)  | NOT NULL                        |
| Modello                | VARCHAR(50)  | NOT NULL                        |
| Immatricolazione       | YEAR         | NOT NULL                        |
| Foto                   | TEXT         | NOT NULL                        |
| Motore                 | VARCHAR(50)  | NOT NULL                        |
| Colore                 | VARCHAR(15)  | DEFAULT                         |
| Targa                  | CHAR(7)      | NOT NULL, UNIQUE                |
| Chilometraggio         | FLOAT(6,3)   | NOT NULL                        |
| Carburante             | VARCHAR(20)  | NOT NULL                        |
| Tipo di cambio         | VARCHAR(20)  | NOT NULL                        |
| Classe di emissioni    | VARCHAR(20)  | NOT NULL                        |
| Precedenti proprietari | TINYINT      | NOT NULL                        |
| Prezzo                 | FLOAT(6,3)   | NOT NULL                        |