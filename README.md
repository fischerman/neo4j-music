# neo4j-music

This repo is for educational purpose and includes a simple Neo4j dataset

## Queries

Every file contains a cypher query

- create: Creates a dataset containing artist, publications, labels, customers and purchases
- recommendation: "People who bought 25 also bought this ...". Returns publications that have been purchased by customer who also bought 25 ordered by total number of purchases
- recommendation-user: An extension of the previous pattern, that is based on the customer Eve. It excludes every album that has been purchased by Eve already
