# check-the-type-of-triangle-
print equilateral , isosceles or scalene


#include<iostream>
using namespace std ;
int main(){
  int a,b,c;
  cin>>a>>b>>c;
  if((a+b)>c||(b+c)>a||(c+a)>b){
      if (a==b&&b==c)
      cout<<"1"<<endl;
      else if (a==b||b==c)
      cout<<"0";
      else
      cout<<"-1";
      
  }
  else
  cout<<"invalid triangle "<<endl;
  
  
  
  
    return 0;
}
