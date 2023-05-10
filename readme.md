# *Database Used cars*
---
## table name: cars
## entity name: car
## table columns:
--- Data types ---  

- id                     | BIGINT  PK  AI  NOTNULL  UNIQUE  INDEX
- brand                  | VARCHAR(50)     NOTNULL          INDEX
- model                  | VARCHAR(80)     NOTNULL          INDEX
- price                  | DECIMAL(8,2)    NOTNULL          INDEX
- transmission           | VARCHAR(20)     NULL
- img                    | VARCHAR(255)    NULL
- km_age                 | VARCHAR(6)      NOTNULL
- fuel                   | VARCHAR(15)     NULL
- year                   | YEAR            NULL
- type                   | VARCHAR(15)     NULL
- emissions_class        | CHAR(6)         NULL
- doors                  | TINYINT         NULL
- color                  | VARCHAR(15)     NULL
- cv/kw                  | TINYINT         NULL
- gear                   | TINYINT         NULL
- displacement           | VARCHAR(10)     NULL
