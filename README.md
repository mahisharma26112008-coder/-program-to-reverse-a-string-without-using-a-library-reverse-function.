# -program-to-reverse-a-string-without-using-a-library-reverse-function.

#include<iostream>
#include<iostream>
  using namespace std;
   int main(){
       string str;

       cout<<"enter a string";
       getline(cin,str);

       cout<<"reveresed string";
       for(int i=str.length()-1;i>=0;i--){
           cout<<str[i];
       }

       return 0;
   }
