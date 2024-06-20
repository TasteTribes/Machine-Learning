from neo4j import GraphDatabase

# URI examples: "neo4j://localhost", "neo4j+s://9d1381c2.databases.neo4j.io:7687"
URI = "<neo4j+s://9d1381c2.databases.neo4j.io:7687>"
AUTH = ("<Shirley>", "<Sxl9950312>")

with GraphDatabase.driver(URI, auth=AUTH) as driver:
    driver.verify_connectivity()