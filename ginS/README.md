#Gin Default Server

This is API experiment for Gin.

```go
package main

import (
	"github.com/korrolion/gin"
	"github.com/korrolion/gin/ginS"
)

func main() {
	ginS.GET("/", func(c *gin.Context) { c.String("Hello World") })
	ginS.Run()
}
```
