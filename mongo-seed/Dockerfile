FROM mongo

#COPY c:/mongo/booksJson.js data/db/booksJson.js

CMD mongoimport --host mongodb --collection books --type json --file /data/booksJson.js --jsonArray
