# Warehouse Schema

A warehouse schema is a blueprint for organizing data in a data warehouse then optimize it for reading.

## Two Types of Schema

### 1. Star Schema
- Has few joins
- Has fast queries
- Mostly common in Business Intelligence

### 2. Snowflake Schema
- Normalized dimensions tables
- Saves storage, more complex joins
- Has slow queries
- Also hard to maintain

---

## Anatomy of a Star Schema (The Two Tables)

| Fact Table | Dimension Tables |
|------------|------------------|
| Foreign key to dimensions | Textual, categorical |
| Very long | Relatively short |
| Changes frequently | Changes slowly |
| Sparse (many columns) | Wide |
| Every row = an event | Every row = an entity |

---

## Types of Fact Tables

1. Transactional
2. Periodic snapshot
3. Accumulated snapshot
4. Factless Fact

---

## Types of Dimension Tables

1. Conformed
2. Degenerate
3. Junk
4. Role-playing
5. Outrigger

---

## Star Schema Rules

| Rule | Explanation |
|------|-------------|
| One fact table per business process | Don't mix sales and inventory in same fact |
| Surrogate keys for dimensions | Use meaningless integers, not business IDs |
| Dimensions are wide, facts are deep | Many columns vs many rows |
| No text in fact tables | Only numeric measures and foreign keys |
| Consistent grain | Every row in fact table represents same level of detail |
| Conform dimensions | Same dimension definition across all fact tables |