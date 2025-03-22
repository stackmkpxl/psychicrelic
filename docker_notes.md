https://dev.to/docker/how-to-run-microsoft-sql-in-minutes-using-docker-desktop-3h7d


docker ps

docker exec -it abafdd33ef5f bash



abafdd33ef5f

mysql -u root -p


docker exec -it abafdd33ef5f /opt/mssql-tools18/bin/sqlcmd -S localhost:1433 -U sa -P yourStrongPassword1


docker exec -it abafdd33ef5f /opt/mssql-tools18/bin/sqlcmd -S 127.0.0.1 -U sa -P yourStrongPassword1








WAL used in nosql databases