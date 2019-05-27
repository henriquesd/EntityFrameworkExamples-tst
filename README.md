# Some Entity Framework Commands:

To install Entity Framework, open the Package Manager Console and execute:
- install-package EntityFramework -Version:6.1.3

To enable migrations:
- enable-migrations

To create a migration:
- add-migration Migration_Name

To update the database:
- update-database



------------------------------------------------------------------------------
Others

To allow null on DateTime field, need to use the question mark:
- public Datetime? DatePublished { get; set;}




Connection Strings example (code first):

<connectionStrings>
	<add name="DefaultConnection" connectionString="data source=.\SQLEXPRESS; initial catalog=EFExample; integrated security=SSPI" providerName="System.Data.SqlClient"/>
</connectionStrings>


