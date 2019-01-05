# C-Pengiriman-parameter-fungsi-berupa-array-dimensi-1

    #include <stdio.h>
    #include <conio.h>

    int cetak_mundur (char S []){
    int i,n;
    for (n=0;n<S[n];n++);
    printf ("Panjanng array = %d\n",n);
    for (i=n-1;i>=0;i--){
    printf ("%c",S[i]);
    }
    }
    int main (){
    char str [50]="RAFI ALWAN SETYAWAN";
    cetak_mundur (str);
    }
    
Hasil
![img](https://github.com/Rafflesia3/C-Pengiriman-parameter-fungsi-berupa-array-dimensi-1/blob/master/C++%20Pengiriman%20parameter%20fungsi%20berupa%20array%20dimensi%201.png?raw=true)
