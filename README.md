# golang测试自有包库


调用包仓库
首先: go get go get github.com/zhukunJ/common-tools-private ，然后随意写个go测试文件，看看是否可以测试成功
package main

import (
	"fmt"
	"github.com/zhukunJ/common-tools-private"
)

func main() {

	ip := common_tools_private.GetLocalIp()
	fmt.Println("ip", ip)

}

