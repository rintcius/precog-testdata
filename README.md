# precog-testdata

gzip -k *.json

cp <filename> <filename>.corrupt
truncate --size=-1 <filename>.corrupt
