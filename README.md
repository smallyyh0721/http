# http
html and http test
get:
    curl -v 192.168.33.1:8080/girls/age/18

post:
    curl -v 192.168.33.1:8080/girls -d 'age=14&cupSize=C'
    curl -v -X POST 192.168.33.1:8080/girls -d 'age=14&cupSize=C'

put:
    curl -v -X PUT -d "age=19&cupSize=C" 192.168.33.1:8080/girls/3

delete:
    curl -v -X DELETE 192.168.33.1:8080/girls/3
