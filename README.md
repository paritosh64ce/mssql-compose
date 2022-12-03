
- Build using
  > docker-compose up -d

- Once up, connect using
  > docker exec -it sql-server-db "bash"

- It  will show prompt like below
  > mssql@391c99005fef:/$

  > /opt/mssql-tools/bin/sqlcmd -S localhost -U sa -P strong_password
  > USE eCart  
  > GO  
  > SELECT * FROM Category
  > GO  
  > INSERT INTO Category VALUES ('Bag', NULL)  
  > EXIT

  > mssql@391c99005fef:/$ exit