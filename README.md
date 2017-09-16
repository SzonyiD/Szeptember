#include <iostream>

using namespace std;

int main()
{
    int a,b,c,S,P;
    float q;

    setlocale(LC_ALL,"hun");

    cout<<"Első szám="; cin>>a;
    cout<<"Második szám="; cin>>b;
    cout<<"Harmadik szám="; cin>>c;

    S=a+b+c;

    P=a*b*c;

    q=S/3;

    cout<<"Számok összege="<<S<<endl;
    cout<<"Számok szorzata="<<P<<endl;
    cout<<"Számok számtani középarányosa="<<q;

    return 0;
}
