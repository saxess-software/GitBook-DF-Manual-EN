### Database

The core of DataFactory is a database contained on an MS-SQL server. There are two possibilities for data storage:

1. The database is stored in the local intranet
2. The database is stored in a Cloud.

### API

An API is installed on the database that defines the logic of the access control system. In simple terms, the API is a collection of stored procedures which are applied to the database. They contain the access and calculation algorithms which govern all of the processes stored within the database. The API creates the core of DataFactory. All information and commands input in the Excel or web client will effect an action by the API.

