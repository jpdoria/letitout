# Go Let It Out

Go Let It Out by Oasis  
Standing On The Shoulder Of Giants (2000)

## Installation

```bash
go get -u github.com/jpdoria/letitout
```

## Usage

```golang
package main

import (
	"fmt"

	"github.com/jpdoria/letitout"
)

func main() {
	line := letitout.GetLine()

	fmt.Println(line())
	fmt.Println(line())
	fmt.Println(line())
}
```

### Example

```bash
➜ go run sing.go
♪ Paint no illusion, try to click with whatcha got ♪
♪ Taste every potion 'cause if yer like yerself a lot ♪
♪ Go let it out, go let it in, go let it out ♪

2018-11-16 4:52:34 in /tmp via 🐹 v1.11.2
➜
```
