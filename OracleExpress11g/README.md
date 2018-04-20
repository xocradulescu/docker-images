# Oracle 11.2.0.1.0 Express Edition

REQUIRED FILES TO BUILD THIS IMAGE
----------------------------------
`oracle-xe-11.2.0-1.0.x86_64.rpm.zip`

Download Oracle Database 11g Release 2 Express Edition for Linux x64
from [here](http://www.oracle.com/technetwork/database/database-technologies/express-edition/downloads/index.html)
place it in the `OracleExpress11g` folder

BUILD AND RUN STEPS
------------------
`docker-compose up -d`

USING THE DATABASE
------------------
update the SYS and SYSTEM passwords:
`docker exec -ti oracle-db setPassword.sh <password>`

EXTRA
-----
For more details about how to use this image please read [this](https://github.com/oracle/docker-images/blob/master/OracleDatabase/SingleInstance/README.md)


