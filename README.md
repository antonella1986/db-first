## Table name: "auto"

# Table columns

- ID - primary key - auto_increment - NOTNULL
- brand: VARCHAR - NOTNULL
- modello: VARCHAR -NOTNULL
- cilindrata: INT - NOTNULL
- cavalli: INT - NOTNULL
- colore: VARCHAR - NOTNULL
- anno immatricolazione: YEAR NOTNULL
- km: INT - NOTNULL
- numero porte: SMALLINT - NOTNULL
- prezzo: INT - NOTNULL
- disponibilità: TINYINT DEFAULT(1) - NOTNULL
- alimentazione: VARCHAR - NOTNULL
- tipo cambio: VARCHAR - NULL
- tipo carrozzeria: VARCHAR - NOTNULL
- stato: VARCHAR - NOTNULL
- dimensioni: VARCHAR - NULL
- descrizione: TEXT() - NULL