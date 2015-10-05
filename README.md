# factorial
my first repository
#include<iostream .h>
#include<conio .h>
 
void main()
{
  int fact = 1, N;
  clrscr();
 
  cout< <endl<<"Enter a number\n";
  cin>>N;
 
  for( int i=1; i< =N; i++ )
   fact = fact * i;  // OR fact *= i;
 
  cout<<endl<<endl<<"Factorial of "<<N<<" is "<<fact;
 
  getch();
}
