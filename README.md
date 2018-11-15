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

	fmt.Println(line()) // ♪ Paint no illusion, try to click with whatcha got ♪
	fmt.Println(line()) // ♪ Taste every potion 'cause if yer like yerself a lot ♪
	fmt.Println(line()) // ♪ Go let it out, go let it in, go let it out ♪
}
```
