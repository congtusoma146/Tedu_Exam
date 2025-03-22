# Tedu exam Project

## Docker command Example
// Docker run Myssql
- docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=xuanphuong@2811" -p 1433:1433 -d mcr.microsoft.com/mssql/server:2022-latest 
// Docker run MongoDB
-  docker run -d --name some-mongo -e MONGO_INITDB_ROOT_USERNAME=admin -e MONGO_INITDB_ROOT_PASSWORD=xuanphuong@2811 -p 127.0.0.1:27017:27017 mongo