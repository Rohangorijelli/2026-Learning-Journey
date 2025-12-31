## I'll update my day to day learnings of my SQL/Database related topics here.

# 30-12-2025 

**Completed the Following Workshop - [text](https://www.freecodecamp.org/learn/relational-databases-v9/workshop-database-of-video-game-characters/build-a-database-of-video-game-characters)**

# Created below database 

mario_database=> \d more_info
                                        Table "public.more_info"
+--------------+--------------+-----------+----------+-------------------------------------------------+
|    Column    |     Type     | Collation | Nullable |                     Default                     |
+--------------+--------------+-----------+----------+-------------------------------------------------+
| more_info_id | integer      |           | not null | nextval('more_info_more_info_id_seq'::regclass) |
| birthday     | date         |           |          |                                                 |
| height       | integer      |           |          |                                                 |
| weight       | numeric(4,1) |           |          |                                                 |
| character_id | integer      |           | not null |                                                 |
+--------------+--------------+-----------+----------+-------------------------------------------------+
Indexes:
    "more_info_pkey" PRIMARY KEY, btree (more_info_id)
    "more_info_character_id_key" UNIQUE CONSTRAINT, btree (character_id)
Foreign-key constraints:
    "more_info_character_id_fkey" FOREIGN KEY (character_id) REFERENCES characters(character_id)

# 31-12-2025 

# Summary Of PostgreSQL - [text](https://www.freecodecamp.org/learn/relational-databases-v9/review-sql-and-postgresql/review-sql-and-postgresql)

By following the Workshop and course([text](https://www.freecodecamp.org/learn/relational-databases-v9)) I have learn't the basic SQL and Relational database concepts listed below.

As a part of course I built game characters databases using PostgreSQL.

While performing the above workshop. I have touchbased core basic concepts like 

- Connecting to the terminal using psql
- Navigating through the databases
- command line short cuts 
- how to read my datbase details from CLI
- Reading my table details from CLI
- Creating Databases,Tables and Columns with Constraints.
- Relationships between differet tables.
- DMLs/DDLs/DCLs

## Will update more detailed notes here.
