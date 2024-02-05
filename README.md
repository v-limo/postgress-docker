
# Postgres

```bash
docker run --name postgresdatabase -p 5432:5432 -e POSTGRES_PASSWORD=mysecretp@ssword! -d postgres
```
## Connection String
```bash
# Connection strings
 "DefaultConnection" : "Host=localhost;Port=5432;Database=postgres;Username=postgres;Password=mysecretp@ssword!;"
```

# MySQL
```bash
docker run -e "ACCEPT_EULA=1" -e "MSSQL_SA_PASSWORD={password}" -e "MSSQL_PID=Developer" -e "MSSQL_USER=SA" -p 1433:1433 -d --name=sql mcr.microsoft.com/azure-sql-edge
```
