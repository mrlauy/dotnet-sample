
start a development env
```bash
docker run --rm -it -v $PWD:/work -w /work mcr.microsoft.com/dotnet/core/sdk /bin/bash
```


```bash
dotnet new console -o program
dotnet new webApp -o site
```

```bash
docker-compose up
```
