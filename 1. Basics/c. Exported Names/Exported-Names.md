Pada bahasa go, ketika kita mau mengakses konstanta, fungsi atau method. Kita dapat memanggil seperti berikut:

```
 package main

 import (
    "fmt"
    "math"
 )

 func main(){

   //Cara memanggil konstan
   fmt.Println("Ini adalah Nilai ", math.Pi)

  // Cara memanggil fungsi atau method
   fmt.Println("Ini adalah akar dari 25 = %.1f", math.Sqrt(25))
 
 }
```

Jika kita lihat dari kode diatas baik  nilai konstan dan fungsi diawali dengan huruf kapital (*math.Pi* dan *math.Sqrt()*).

Dalam bahasa go, nilai konstan dan fungsi yang dapat digunakan pada kode program yang lain, harus diwalai dengan huruf kapital. Ini dinamakan dengan **Exported Names**.

Kemudian, nilai konstan dan fungsi yang tidak diawali dengan huruf kapital maka tidak bisa digunakan oleh kode program yang lain dan hanya berlaku internal pada file tersebut. Ini dinamakan dengan **Unexported Names**.
