# konversi-waktu


#include<iostream>
using namespace std;
int main ()
{
    int s,hari,jam,menit,detik,sisa;
    cout<<"Konversi Detik ke Hari, Jam, Menit, Detik"; cout<<endl;
    cout<<"Masukan Detik ="; cin>>s;
    hari = s/3600/24;
    jam  = s/3600;
    sisa = s%3600;
    menit= s/60;
    detik= sisa%60;
    cout<<hari<<"Hari\n"<<jam<<"Jam\n"<<menit<<"Menit\n"<<detik<<"Detik\n"<<endl;
    return 0;
}





