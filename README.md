# Database Images

## Before you begin

### Software Required
1. Postgres, Oracle & Neo4j can be access by a a dababase tool like [DBeaver](https://dbeaver.io/download/)
2. MongoDB can be access by a dababase tool like [Studio 3T](https://studio3t.com/download/)

### Windows User
1. Download [Docker Desktop for Windows](https://docs.docker.com/desktop/install/windows-install/)
2. Familiarize yourself with [Docker Compose CLI](https://docs.docker.com/compose/reference/)

### Mac User
1. Download [Docker Desktop for Mac](https://docs.docker.com/desktop/install/mac-install/)
2. Familiarize yourself with [Docker Compose CLI](https://docs.docker.com/compose/reference/)


## Running
1. Make sure that you are in the directory of the compose.yaml file you want to run in either Treminal(Mac User) or Compand Prompt(Windows User).
2. Run the following to start the image:
```
docker compose up
```
3. Run the following to stop the image:
```
docker compose down
```

## Authentication

### MongoDB
No password required to connect database in Studio 3T

### Neo4j
No password required to connect database in DBeaver

### Oracle
[Container Repo Documentation](https://container-registry.oracle.com/ords/f?p=113:4:106321665818527:::4:P4_REPOSITORY,AI_REPOSITORY,AI_REPOSITORY_NAME,P4_REPOSITORY_NAME,P4_EULA_ID,P4_BUSINESS_AREA_ID:803,803,Oracle%20Database%20Express%20Edition,Oracle%20Database%20Express%20Edition,1,0&cs=3_r_JOKKYmOTaSKUnCZPMqtWXbvOOi8VgqIQIjREF_FiaF0sHjPB9j46Wrd0zZmnd0sG6rek8XXmznfwlDCEtFA)

[Performance & Storage Indicators](https://localhost:5500/em/) 
- Username: SYSTEM   
- Password: P@ssw0rd1!


To connect database in DBeaver
- Host: localhost
- Port: 1521
- Database: XE
- Username: SYSTEM
- Role: Normal
- Password: P@ssw0rd1!

### Postgres
To connect database in DBeaver
- Host: localhost
- Port: 5432
- Database: postgres
- Username: postgres   
- Password: postgres