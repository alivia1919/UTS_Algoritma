# UTS_Algoritma

**NAMA 	: NUR ALI MUHAMMAD**

**KELAS	: TI.18.A.2**

**NIM	: 311810355**

## soal1.cpp

**Alur Program :**

1. Deklarasi variable `A,B,X,Y` sebagai variable input
2. Menbaca input keyboard `cin >> A >> B >> X >> Y >>`
3. Membandingkan Variable **X** dengan **Y** jika sama
4. karna statement **false** tidak akan terjadi ```{X!=Y}```
5. dan jika statement **True** maka akan terjadi `X < Y` berlaku rumus statement **true** dengan syntax `X = X + A`
7. dan jika statment **False** maka hasilnya  `Y = Y + B`
8. Disini akan terjadi pengulangan untuk mencari nilai **X**
9. Dan terakhir akan tercetak `X = X + A = (hasilnya)`.

**Code Program :**

```c++

#include<iostream>

using namespace std;
int main()
{
    int A,B,X,Y;
    cout<<"Masukan Nilai A : ";
    cin>> A;
    cout<<endl;
    cout<<"Masukan Nilai B : ";
    cin>> B;
    cout<<endl;

    X=A;
    Y=B;

    while(X!=Y)
        {if (X<Y)
        {
            X=X+A;
        }
    else{
            Y=Y+B;
        }

    }
    cout<<"Hasilnya adalah : "<< X <<endl;
    cin.get();
}

```

**Hasilnya yang pertama :**

![hasilnya](https://raw.githubusercontent.com/alivia1919/UTS_Algoritma/master/soal1/hasil1.png)

**Hasilnya yang kedua :**

![hasilnya](https://raw.githubusercontent.com/alivia1919/UTS_Algoritma/master/soal1/hasil2.png)

## soal2.cpp

**Alur Program :**

1. Deklarasi varaible input `N,X,T, Batas;` sebagai inputnya
2. Memasukan nilai **N** yaitu 2 digit terakhir dari NIM saya, maka **N** adalah `55` dan batasnya adalah 195 dari hasil jumlah `N + 140`
3. Masukan variable **X**, dan **T, X** nya adalah **20** dan kemudian **T** adalah `55` (dari N)
4. Dimana **T** kurang dari sama dengan **Batas**, berarti tidak boleh melebihi batas
5. Kemudian menghitung `X = X + 10;` , dan hasilnya adalah **30** 
6. Kemudian menghitung `T = T + X;` hasilnya adalah **75**
7. Kemudian cetak variable **T**.

**Code Program :**

```c++

#include<iostream>
using namespace std;

int main()
{
    int N,X,T,Batas;
    N = 55 ;
    Batas = N + 100;
    X = 20;
    T = N;
    while( T <= Batas)
{ T = T + X;
X = X + 10;
}
cout <<"Hasilnya adalah : " << T;
}
 
```

**Hasilnya :**

![hasilnya](https://raw.githubusercontent.com/alivia1919/UTS_Algoritma/master/soal2/hasil.png)


**TERIMA KASIH** 
# UTS_Algoritma