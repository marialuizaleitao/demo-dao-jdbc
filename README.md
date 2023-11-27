# JDBC Project

## Overview

This project dives into JDBC, a tool for connecting Java applications with relational databases. It blends theory and hands-on practice to equip developers with skills for robust and scalable Java applications. The project focuses on manually implementing the DAO (Data Access Object) pattern, an approach for encapsulating data access logic and ensuring loose coupling between application layers.

![diagram](https://github.com/marialuizaleitao/demo-dao-jdbc/assets/88951059/0c89e707-e199-484d-a2de-5673c7b22b1b)


## Technologies Used

`Java`: Core functionality development.<br/>
`JDBC`: Harnessing JDBC's capabilities to seamlessly interact with the MySQL database.<br/>
`MySQL Java Connector`: Establishing a robust connection between the Java application and the MySQL database.<br/>
`User Libraries`: Employing User Libraries in Eclipse to manage external dependencies effectively.<br/>

## Challenges and Solutions

*Optimizing Data Retrieval Performance:* To efficiently retrieve department information, the project used PreparedStatements, ensuring minimal database queries and maximizing performance.

*Handling Integrity Exceptions:* To safeguard data integrity, the DbIntegrityException class was created, capturing and handling referential integrity violations.

## Contributions

*DAO Pattern Implementation:* Manual implementation of the DAO pattern, demonstrating a thorough understanding of object-oriented design principles and data access layer architecture.

*Coding Best Practices Adherence:* Enforced coding best practices throughout the project, ensuring maintainability and adherence to industry standards.

*Test-Driven Development:** Integrated unit tests to guarantee the robustness and reliability of the application's core functions.

## Next Steps

*Transaction Management Implementation:* Introduce transaction management to ensure data consistency and integrity across multiple operations.

*Object-Relational Mapping (ORM) Integration:* Explore the integration of ORM frameworks to streamline data access.

*Extensive Unit Testing Expansion:* Expand the test suite to cover a wider range of scenarios and enhance code coverage.

# Conclusion

This project enhances JDBC skills,the importance of coding best practices and software design principles. By delving into data access layers, the application showcases a deep understanding of database manipulation in a Java context, elevating the quality and efficiency of software development.
