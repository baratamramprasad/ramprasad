# Cassandra

To keep the scalability and be make each microservice indepentantly scalable, for every microservice, we shall have one keyspace shall be defined.
Microservices will be communicated using Kafka for any data change in keyspace.One mocro service shall be allowed to read other keyspace.

## Entity Relationship Diagram

* [DataModel](https://viewer.diagrams.net/?title=DataModel.drawio#Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fbaratamramprasad%2Framprasad%2Fmaster%2FArchitecture%2520Documents%2FDataModel.drawio)

+ Note: This shall be considered as independant Git repository for better collabation across the teams
