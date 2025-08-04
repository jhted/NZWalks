```
docker network create -d bridge nzwalks-network
```
```
docker-compose up -d
```
```
NZWalks\NZWalksAPI>
dotnet ef migrations add InitioalMigration
 dotnet ef database update
```