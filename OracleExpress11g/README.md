# Oracle 11.2.0.1.0 Express Edition

REQUIRED FILES TO BUILD THIS IMAGE
----------------------------------
`oracle-xe-11.2.0-1.0.x86_64.rpm.zip`

Download Oracle Database 11g Release 2 Express Edition for Linux x64
from [here](http://www.oracle.com/technetwork/database/database-technologies/express-edition/downloads/index.html)
place it in the `OracleExpress11g` folder

BUILD AND RUN STEP
------------------
run `docker-compose up -d` to build the image and run the container

USING THE DATABASE
------------------
connect to the database container:
`docker exec -ti oracle-db /bin/sh`

update the SYS and SYSTEM passwords:
`./setPassword.sh <password>`


