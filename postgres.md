## Open psql
sudo -u postgres psql

## Open data base
\c databasename

## Import csv file into table
COPY tablename FROM filename DELIMITER ';' CSV HEADER; 
