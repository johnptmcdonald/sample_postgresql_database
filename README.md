# Using the IMDB database in PostgreSQL

## Usage
Create a database called _imdb-sample_:

You can do this from your regular command line:
`$ createdb imdb-sample`

Or from your psql cli:
`> CREATE DATABASE imdb-sample;`

Then from the command line run pgrestore:
`pg_restore -d imdb-sample imdb-sample.tar`


