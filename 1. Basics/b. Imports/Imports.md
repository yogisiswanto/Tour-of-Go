# Imports

Dalam bahasa go, kita bisa menambahkan package lain kedalam kode yang sedang kita kerjakan dengan menambahkan kata *import path/namaPackage*

Berikut ini contohnya menambahkan package sekaligus

```
package main

import (
  "fmt"
  "math"
)
```

Selain itu, kita juga bisa menambahkan package lain satu-satu seperti berikut

```
package main

import "fmt"
import "math"
```
