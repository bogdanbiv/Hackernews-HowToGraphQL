# Hackernews-HowToGraphQL
The Fullstack Tutorial for GraphQL - Maira Bello

docker pull mongo
docker run --name mongoContainer --restart=always -d -p 8080:8080 mongo mongod --auth
sudo docker exec -i -t mongoContainer bash
mongo
use admin
db.createUser({user:"bog", pwd:"mamaliga9", roles:[{role:"root", db:"admin"}]})
exit && exit

