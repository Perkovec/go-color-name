# go-color-name

A JSON with color names and its values. Based on http://dev.w3.org/csswg/css-color/#named-colors.

Port of [color-name](https://github.com/colorjs/color-name) package

Installing
```bash
go get github.com/Perkovec/go-color-name
```

Usage
```golang
package main

import (
    "fmt"
    "github.com/Perkovec/go-color-name"
)

func main() {
    fmt.Println(colorname.Name["red"]) // [255 0 0]
}
```