# Appengine

Implements appengine Log interface

```
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
