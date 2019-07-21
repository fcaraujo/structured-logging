# Using Structured Logging in .NET Core 2.2, Serilog, Kibana and ElasticSearch

## How to run
- Restore
- Run docker containers
- Debug

### Restore

Restore project using `dotnet restore`

### Run docker containers (elastic search and kibana):
```
cd src/docker
docker-compose up -d
```
Check http://localhost:5601/ (kibana) and http://localhost:9200/ (elastic)

### Open Solution and debug

Open project in VSCode or Visual Studio for debug project hitting F5


### TODO List
- Add Seq filter 
- Use scopes
- Add Oracle Db Logging provider example