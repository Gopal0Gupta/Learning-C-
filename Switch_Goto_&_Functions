#include<iostream>
using namespace std;

int nNatural(int n,int x){
  int sum = 1, j = 1, k = 1;
  switch(x){
    case 1: for(int i=1;i<=n;i++){
              sum = sum*i; 
            }
            return sum;
            break;
    case 2: while(j<=n){
              sum = sum*j;
              j++;
            }     
            return sum;
    case 3: do{
              sum = sum*k;
              k++;
            }while(k<=n);
            return sum;
  }
}

int main()
{ int N,X;
  string str;
  cout<<"enter a number to find the sum of natural number :-> "<<endl;
  cin>>N;
  label :
  cout<<"enter 1 to find sum using   for loop :->"<<endl;
  cout<<"enter 2 to find sum using   while loop :->"<<endl;
  cout<<"enter 3 to find sum using   do while loop :->"<<endl;
  cin>>X;
  int sum = nNatural(N,X);
  cout<<"The sum of the "<<N<<" natural number is :-> "<<sum<<endl;
  cout<<"Want to continue again with different method [y,n] :-> "<<endl;
  cin>>str;
  if(str == "y" || str == "Y" ){
    goto label;
  }
  else{
    goto exit;
  }
  exit :
  return 0;
}
