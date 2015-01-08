# linodego
---

### Overview

Package linodego is an unofficial Go client implementation for [Linode](http://www.linode.com) API.
Check the Linode API documentation for details:
[https://www.linode.com/api](https://www.linode.com/api)

Current API implementation supports using api_key request parameter. All
requests are sent using POST methods. 

`TODO`: Batch request is not implemented yet.

### Example

Check examples/client.go for sample usage. Note that you must supple API Key
in examples/client.go before running the program:

```
go run examples/client.go
```

### Test
Update API Key in api_key_test.go, then run:

```
go test
```

### Installation

```
go get "github.com/taoh/linodego"
```

### Package

```
import "github.com/taoh/linodego"
```

