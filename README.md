# EmployeeService

Used :  Spring Web flux(Reactive Spring REST API), Cassandra DB, Kafka(producer), Hazelcast

Implemented a Springboot REST endpoint - createEmployee - that will persist the employee information into Cassandra database.

Implemented a Kafka producer that posts the employee information received from the createEmployee REST endpoint into a Kafka topic.

Implemented a Springboot REST endpoint - findEmpSkillSet - that fetches a list of employees from Cassandra matching the input(java exp).
