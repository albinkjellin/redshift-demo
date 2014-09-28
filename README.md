redshift-demo
=============

Example Mule flows for how to import data into amazon redshift from a mysql database.

Prerequirements

Amazon S3
Amazon Redshift with a contacts table.
MySQL Instance with a contacts table.

Fill in the following details:

redshift.url=
redshift.port=
redshift.database=
redshift.username=
redshift.password=
mysql.host=
mysql.port=
mysql.database=
mysql.username=
mysql.password=
aws.access.key=
aws.secret.key=

Run create table statement on each of the databases.

Polulate the mysql database with sample data.

Run the application from studio by hitting:
http://localhost:8881/copy

