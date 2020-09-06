# Write-a-program-to-find-x-to-the-power-n-i.e.-x-n-.-Take-x-and-n-from-the-user.-You-need-to-print-t



#include<iostream>
using namespace std;

int main() {
	int x,n;
    int i=1;
    int res=1;
    cin>>x>>n;
    if(n==0)
    {
        cout<<1;
    }
    else if((n==0)&&(x==0))
    {
        cout<<1;
    }
    else{
    while(i<=n)
    {
        res=res*x;
        i++;
    }
        cout<<res;
    }
    
	
}
