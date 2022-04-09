# Write-a-C-program-to-compute-expression-values-and-print-the-results-as-required
Write a C++ program to compute expression values and print the results as required
#include <cstdlib>
#include <iostream>
 
using namespace std;
 
int main(int argc, char *argv[])
{
int x;
int y;
x=18;
y=2;
cout<<"Pass through check:\n";
cout<<"Grid x\t"<<"Gtri y\t"<<"Understanding\t"<<"Pass through\n";
cout<<x<<" |\t"<<y<<" |\t"<<"A=y+3\t"<<"\t|"<<"A="<<y+3 <<"\n";
cout<<x<<" |\t"<<y<<" |\t"<<"B=y-2\t"<<"\t|"<<"B="<<y-2 <<"\n";
cout<<x<<" |\t"<<y<<" |\t"<<"C=y*5\t"<<"\t|"<<"C="<<y*5 <<"\n";
cout<<x<<" |\t"<<y<<" |\t"<<"D=x/y\t"<<"\t|"<<"D="<<(float) (x/y)<<"\n";
cout<<x<<" |\t"<<y<<" |\t"<<"E=x%y\t"<<"\t|"<<"E="<<x%y <<"\n";

return 0;
}
