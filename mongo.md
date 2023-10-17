wsl docker run -d -p 27017:27017 --name mongo --user mongodb mongo:4.4


docker exec -it mongo mongo
or use the console directly in portainer > mongo gets to shell

show dbs            (shows all)
use nodegoat        (select DB)
show collections    (show tables)
db                  (show selected DB)
db.users.find()     ( select all - opt .pretty())


