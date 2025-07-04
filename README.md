# db-first

## 🚗 Modello Database - Auto Usate in Vendita

- id                    | BIGINT            | PRIMARY_KEY AUTO_INCREMENT NOTNULL UNIQUE
- brand                 | VARCHAR(50)       | NOTNULL
- model                 | VARCHAR(50)       | NOTNULL
- registration_year     | YEAR              | NOTNULL
- km                    | INT               | NOTNULL
- fuel                  | VARCHAR(30)       | NOTNULL
- price                 | DECIMAL(10, 2)    | NOTNULL
- color                 | VARCHAR(15)       | NULL
- description           | TEXT              | NULL
- image                 | VARCHAR(255)      | DEFAULT ("<https://defaultImage/>")
- is_sold               | TINYINT           | NOTNULL