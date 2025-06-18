> [language](../)

![banner](/go/photos/banner.png)

## Packages

> People run in packs because they don’t feel safe alone.  
> I run alone because I don’t feel safe in packs.  
> **Muhammad Ali**

The primary unit of organization in a Go program is the package.  A package consists of one or more files that reside in the same folder.  A file consists of _import_, _constant_, _variable_, _type_ and _function_ declarations.  It is conventional to name the folder containing the package with the name of the package.

Packages export identifiers that start in uppercase.  Identifiers in lowercase are visible only inside the package block.  There is no need for scope specifiers.  Simple!

Packages are organized hierarchically inside a folder structure.  The identifier of a lower level package is — conventionally — the path from the top-level package to the lower level package separated by forward slashes.

The package name _main_ is special and the function _main()_ in that package denotes the beginning point of execution in that program.

### Example

```go
// hello.go

package main

import "fmt"

func main() {
    fmt.Println("hello, world!")
}
```

> Here, _fmt_ is the standard formatter package.  Notice that the _Println()_ function — exported by the _fmt_ package — starts with an uppercase letter.
