# golibtest
try to create an go-getable lib


now it's finished can be get by running 
```
go get -u github.com/rightblank/golibtest
```

and import in go programs like all other packages
```
package main

import (
	"fmt"
	"github.com/rightblank/golibtest/stringutil"
)

func main()  {
	fmt.Println(stringutil.Reverse("会挽雕弓如满月 西北望 射天狼"))
}
```

but notice that this is really just a test, that only one method
will not be able to help you too much, but I had fun :)

