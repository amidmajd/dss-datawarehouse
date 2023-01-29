* Install ODBC for sql-server connection to work:
[Download ODBC 18](https://learn.microsoft.com/en-us/sql/connect/odbc/linux-mac/installing-the-microsoft-odbc-driver-for-sql-server?view=sql-server-ver16&tabs=ubuntu18-install%2Calpine17-install%2Cdebian8-install%2Credhat7-13-install%2Crhel7-offline)

* Fix permission issue on mssql-data host volume files:
`sudo chown 10001 mssql-data` [more details](https://stackoverflow.com/questions/65601077/unable-to-run-sql-server-2019-docker-with-volumes-and-get-error-setup-failed-co)
