A teacher manages information about students and lab problems.
Create an application which allows to:
- perform CRUD operations on students and lab problems
- assign problems to students; assign grades
- filter entities based on various criteria
- reports: e.g. find the problem that was assigned most times

Lab 2-4
- design the solution for your problem using a CASE tool (use cases, class diagram,
sequence diagram for each use case)
- use feature driven development
- layered architecture
- data validation
- all functions will be documented and tested
- use Java 8 features (lambda expressions, streams etc); the program should be written
without if statements and loops
- persistence: ‘in memory’, text files, xml, db (jdbc); you may use any RDBMS, but we only
offer support for PostgreSQL; MS SQL Server is forbidden

Lab 5: JDBC
- Continue the project from Lab 2-4 - persistence in DB (using JDBC); MSSQL is
forbidden.
Version 1 (8 p):
- The DB repositories must implement the Repository interface from
catalog1_I1_inmemory_infile.zip (they must not extend the InMemoryRepository class)
Version 2 (10 p):
- The DB repositories must implement the PagingRepository interface from
catalog-paging.zip (they must not extend the InMemoryRepository class)
- In the ui, the entities will be printed using pagination as suggested in the provided
example
- The DB repositories will always load all entities, i.e., pagination will not be implemented
in SQL
- The DB repositories (e.g. findAll(Pageable pageable) method) will delegate pagination
logic to other components

The following iteration plan contains the minimal features such that the starting grade (points) for each iteration is 10:

I1 (deadline week 2):

- two features (e.g: addStudent and printAllStudents)

- java doc in html format (see the example from the group - project_root/doc/index.html - repository interface)

- only inmemory repository is enough

!!! focus on working with git - working on only one branch (master/develop) is enough

→ the project should be of type gradle

I2 (deadline week 3):

- three features

!!! focus on working with git - feature branches must be used

→ the project must be of type gradle

I3 (deadline week 4):

- all features
