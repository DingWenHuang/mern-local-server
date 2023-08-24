FROM mongo

COPY courses.json /courses.json
COPY users.json /users.json

CMD mongoimport --host mongodb --db demoDB --collection courses --type json --file /courses.json --jsonArray && mongoimport --host mongodb --db demoDB --collection users --type json --file /users.json --jsonArray