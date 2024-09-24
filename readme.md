dicker pull neo4j

docker run \
    --publish=7474:7474 --publish=7687:7687 \
    --volume=$HOME/neo4j/data:/data \
    neo4j

docker run --publish=7474:7474 --publish=7687:7687 --volume=$HOME/neo4j/data:/data neo4j

connect using the server sconnection in the browser

bolt://localhost:7687
username: neo4j
password:Lam@415Fer
