# Architecture

![Architecture](images/metamorf-arch.png)

Metamorf is a Python Software that orchestrates, controls and transforms data. From a metadata entry, Metamorf process the metadata to full its system and in exchange grants a series of functionalities that allows to control all your datawarehouse.

Metamorf works with the concept of owner: it can be a user or a use case. Some actions of metamorf can be done selecting an owner, indicated on the configuration file. It can be useful for teamwork using the same Metadata Database and isolating each user or use case under development. Is up to you.

Metamorf stores all the metadata historically, it means that the users can see the status of their datawarehouse in the past at any time and know how the data was processed.

Can fit with other technologies as [dbt](https://www.getdbt.com), giving the code ready to execute. 

An advantage it has, the metadata and data can be on the same database or in separate ones. Thus allowing it to be adaptaded to a greateer number of different architectures and needs.

## Databases
Actually Metamorf supports the following databases:

- Snowflake
- SQLite
- PostgreSQL
- MySQL
