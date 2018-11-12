# Appengine

An [appengine/log][appengine] implemention of `log.Logger`][Logger].
For more on the interface and other implementations, see [the log README][log].

```go
package main

import (
	"context"

	aelog "github.com/go-log/appengine"
)

func main {
	l := aelog.New(context.Background())
	l.Log("a log line")
}
```

[appengine]: https://cloud.google.com/appengine/docs/standard/go/logs/
[Logger]: https://godoc.org/github.com/go-log/log#Logger
[log]: https://github.com/go-log/log/blob/master/README.md
