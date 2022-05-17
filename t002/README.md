# t002

1. 初始化模块
```
go mod init t002
```
2. 编写代码 t002.go
```
package main

import (
	"fmt"

	"rsc.io/quote"
)

func main() {
	fmt.Println(quote.Go())
}

```
3. 导入依赖

```
go mod tidy
```
4. 运行代码

```
go run .
```
