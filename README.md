# Rest + Angular UI + Hibernate Search

Use case: 
- you need all changes on your entities to be logged into an extra audit log.

Run the [LibraryResourceTest.java](src/test/java/org/acme/hibernate/search/elasticsearch/service/LibraryResourceTest.java) and look at the code.
 
    mvn docker:start && sleep 5 && mvn compile test


We are using:
* Quarkus 1.4.2.Final
* Hibernate ORM
* Hibernate Search
* Panache Entity
* Elasticsearch and Postgresql Container


## On testing with Quarkus

- see [TESTING.md](TESTING.md)

## Best practices for Rest implementation

- see [REST.md](REST.md)


---
Base material taken from:

* Quarkus guide: https://quarkus.io/guides/hibernate-search-elasticsearch

