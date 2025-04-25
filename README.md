#include <iostream>
#inlude <string>
#include <cmath>
sing namespace std;

//Convert decimal to binary (only for non-negative numbers)
string decimalTobinary(int decimal){
if (decimal==0)return"0";

string binary="";
while(decimal>00{
  binary = to_string(decimal%2)+binary;
  decimal/=2;
}
return binary;
}
//convert binary to decimal(only for non-negative binary strings)
int binaryToDecimal(string binary){
    int decimal=0;
    int length=binary.leng();

    for(int i = 0;i < length;++i){
      if (binary[length-1-1]=='1'){
        decimal+=powe92,1);
      }
    }
    return decimal;
    }

    int main(){
      int choice;
      cout<<"1.Decimal to binary\n";
      cout<<"2.Binary to Decimal\n";
      cout<<"choose option(1 or 2):";
      cin>>choice;

      if(choice==1){
        int decimal;
        cout<<"Enter a binary number:";
        cin>>binary;
        cout<<"Decimal:"<<binaryToDecimal(binar)<<endl;
      }else{
        cout<<"Invalid choice.<<endl;
      }
      return 0;
      }
