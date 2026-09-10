# Package

Package adalah kumpulan kode-kode go yang saling berkaitan dan dikelompokan dalam satu folder/tempat

Contohnya pada kode main.go. Pada kode tersebut package-nya diberi nama *main*, karena file/kode tersebut berkaitan dengan *package main* pada umumnya.

Selain itu, pada file tersebut mengimport *fmt* dan *math/random*

Artinya file tersebut menambahkan kode dari package *fmt* dan package *rand*

Pada umumnya, nama package sama dengan bagian terakhir dari path import package. Misalkan kita menambahkan package *rand* pada kode kita

```
package main

import "math/rand"

```


maka nama packagenya adalah rand
