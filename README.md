# Praktikum2

## latihann1.cpp program menghitung bilangan terbesar dari 3 bilangan

**Alur Argoritma**
1. Mendeklarasikan Variable int A,B,C sebagai varible input
2. membaca input dari key board  cin >> A >> B >> C
4. membandingkan nilain variable **A** dengan Variable **B** & **C**
5. Jika kondisi **true** Maka cetaklah variable **A**
6. jika **fals** Maka bandingkanlah nilai **B** dengan **C**
7. jika hasil lebih besar **B** **cout** **B** dan sebaliknya

**flowchart program**
![flowchart](https://raw.githubusercontent.com/sofianadi/praktikum2/master/FLOWCHART1.jpg)

**CODE PROGRAM**
'''c++
#include <iostream>

using namespace std;

int main()
{
    int A,B,C;
    cout<<"MASUKAN BILANGAN 1: ";
    cin>> A;
    cout<<"MASUKAN BILANGAN 2: ";
    cin>> B;
    cout<<"MASUKAN BILANGAN 3: ";
    cin>> C;

    if (A>B && A>C) cout << "bilangan terbesar =" << A << endl;
    else
    {
        if (B>A && B>C) cout << "bilangan terbesar = " << B << endl;
        else
            cout << "bilangan terbesar = " << C;

    }
}
'''|

hasilnya :
![img](https://raw.githubusercontent.com/sofianadi/praktikum2/master/screenshot%20latihann1.png)

## latihan2.cpp menghitung bilangan terbesar dari 4 bilangan

**Alur Argoritma**
1. Mendeklarasikan Variable int A,B,C,D sebagai varible input
2. membaca input dari key board  cin >> A >> B >> C >>D
4. membandingkan nilain variable **A** dengan Variable **B** & **C** & **D**
5. Jika kondisi **true** Maka cetaklah variable **A**
6. dan bandingkan nilai  **B** dengan **A**,**C** & **D**
7. jika kondisi **true** maka cetaklah  **B**
8. dan variable **C** dibandingkan lagi **B**,**A** & **D**
9. jika kondisi **true** maka cetaklah **C** 
10. dan jika kondisi **false** maka cetaklah **D**

**flowchart program**
![flowchart](https://raw.githubusercontent.com/sofianadi/praktikum2/master/FLOWCHARTLT2.jpg)
  
**CODE PROGRAM**
'''c++
#include <iostream>

using namespace std;

int main()
{
    int A,B,C,D;
    cout<<"MASUKAN BILANGAN 1: ";
    cin>> A;
    cout<<"MASUKAN BILANGAN 2: ";
    cin>> B;
    cout<<"MASUKAN BILANGAN 3: ";
    cin>> C;
    cout<<"MASUKAN BIANGAN 4: ";
    cin>> D;

    if (A>B && A>C && A>D) cout << "bilangan terbesar = " << A << endl;
    else

    if (B>A && B>C && B>D) cout << "bilangan terbesar = " << B << endl;

    else {
        if (C>A && C>B && C>D) cout << "bilangan terbesar = " << C << endl;
        else
            cout << "bilangan terbesar = " << D;
    }
}

'''|

hasilnya :
![img](https://raw.githubusercontent.com/sofianadi/praktikum2/master/screenshot%20latihan2.png)
