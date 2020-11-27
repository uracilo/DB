FROM mongo:latest 
COPY elements.json /elements.json
CMD mongoimport --host mongo --db utm --collection elements --drop --file /elements.json --jsonArray
