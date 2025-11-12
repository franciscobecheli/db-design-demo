# Database Design Demo

A very small demo of a relational database design built with MySQL Workbench. It includes the Workbench model and SQL scripts to create the schema objects.

![Database diagram](./diagrama_tabelas.png)

## Files

- `diagrama.mwb` — MySQL Workbench model (open to view/edit the ER diagram)
- `tables.sql` — Creates base tables
- `relations.sql` — Adds foreign keys and relationships
- `indexes.sql` — Creates indexes
- `views.sql` — Creates views
- `triggers.sql` — Creates triggers

## How to use

1) Install MySQL (8.x or compatible) and MySQL Workbench.
2) Open `diagrama.mwb` in Workbench to inspect the design.
3) Connect to your MySQL server and select/create a target database (schema).
4) Run the SQL scripts in this order:
   - `tables.sql`
   - `relations.sql`
   - `indexes.sql`
   - `views.sql`
   - `triggers.sql`

That’s it. After running the scripts, you can browse the objects in Workbench or run simple `SELECT` queries to validate the setup.