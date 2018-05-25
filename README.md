# mouse-mover
mouse-mover

```
package main

import (
	"time"

	"github.com/go-vgo/robotgo"
)

func main() {
	for true {
		x, y := robotgo.GetMousePos()
		robotgo.MoveMouse(x+1, y)
		robotgo.MoveMouse(x-1, y)
		time.Sleep(60 * time.Second)
	}
}
```
