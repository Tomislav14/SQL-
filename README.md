# Osnove SQL-a uz DuckDB i Jupyter Notebook

Projekt koji prikazuje korištenje DuckDB, DuckDB-Engine i Jupysql za interaktivno izvršavanje SQL upita unutar Jupyter bilježnica.

## Pregled

Ovaj projekt prikazuje integraciju DuckDB-a, analitičkog sustava za upravljanje bazama podataka, s Jupyter bilježnicama putem Jupysql-a, omogućujući jednostavno izvršavanje SQL upita unutar Python okoline. DuckDB pruža brzu analitičku obradu, a Jupysql omogućuje interaktivno izvršavanje SQL upita unutar Jupyter bilježnica.

## Komponente

### 1. DuckDB

- **Opis:** DuckDB je analitički sustav za upravljanje bazama podataka u memoriji.
- **Ključne Značajke:**
   - Kolonarno pohranjivanje podataka.
   - SIMD i višejezgreni paralelizam za izvršavanje upita.
   - Podrška za SQL upite.
   - Namijenjen analitičkim opterećenjima.
- **Upotreba:** Analiza podataka, interaktivni upiti, poslovna inteligencija.

### 2. Jupysql

- **Opis:** Jupysql omogućuje izvršavanje SQL upita unutar Jupyter bilježnica.
- **Ključne Značajke:**
   - Omogućuje laku integraciju SQL-a s Python kodom.
   - Pruža `%sql` magične naredbe za izvršavanje SQL upita unutar Jupyter-a.
- **Upotreba:** Analiza podataka, istraživanje podataka, suradničko programiranje.

### 3. DuckDB-Engine

- **Opis:** DuckDB sam po sebi može se smatrati pogonom za izvršavanje SQL upita i upravljanje podacima.
- **Napomena:** Izraz "DuckDB-Engine" može se odnositi na osnovne sposobnosti DuckDB-a kao pogona za izvršavanje SQL upita.

## Preduvjeti

- Python (3.6 i više)
- Jupyter Bilježnica
- DuckDB
- Jupysql

## Instalacija

1. Instalirajte DuckDB:

   ```bash
   %pip install duckdb duckdb-engine jupysql
