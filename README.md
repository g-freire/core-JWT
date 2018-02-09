# asp.net core jwt api

### Using Docker:
```diff
+ $ docker build -t aspnetapp .
+ $ docker run -d -p 5000:80 --name myapp aspnetapp
```
#### app running at localhost:5000

### Using asp.net core SDK:

```diff
+ $ dotnet restore && (dotnet build | dotnet run)
```
#### Check API using Postman or other tool
