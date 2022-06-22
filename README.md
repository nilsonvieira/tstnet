# tstnet
Application in Golang for network tests.

# How to use
## Parameters

For get IP from host usage: 
```bash
go run main.go ip --host http://amazon.com.br
```

For get NameServer from host usage: 
```bash
go run main.go ns --host http://amazon.com.br
```

For get StatusCode from url usage: 
```bash
go run main.go ip --url http://amazon.com.br
```

For test netCat from Host and Port usage: 
```bash
go run main.go nc  --host 192.168.0.1 --port 80
```