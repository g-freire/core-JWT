# ASP.NET Core 2 JWT API
 [![Docker Build](https://img.shields.io/docker/build/pierrezemb/gostatic.svg?style=plastic)](https://hub.docker.com/r/gfreire)
 [![Build Status](https://travis-ci.org/PierreZ/goStatic.svg?branch=master)](https://travis-ci.org) 
## Steps to run:
### Using Docker:
```diff
+ $ docker build -t aspnetapp .
+ $ docker run -d -p 5000:80 --name myapp aspnetapp
 ```
 ##### app should be running at localhost:5000

### Using ASP.NET Core 2 SDK:

```diff
+ $ dotnet restore && (dotnet build | dotnet run)
```
##### app should be running at localhost:3000
#
#### Check the service using Postman or your prefered tool:

#### POST method generating token payload for hardcoded credentials
![Screenshot](POST.png)
#
#### GET method response payload using generated token in the authorization header
![Screenshot](GET.png)
