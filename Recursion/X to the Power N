// Pichle number ki power nikalte rhe jbtk wo base case ko hit nhi hogyi, Maan lo x ^ 4 chahiye to partialans me 
// x^3 nikala, fir x^2, fir x^1. X to same hai pr uski value decrease ho rhi hai isiliye hr function call me n-1
// kiya and end me usko x se multiply krke ans return krwadiya 

#include<iostream>
using namespace std;

int power(int x, int n){

    if(n==0)
    return 1;
    
    int partialAns=power(x, n-1);
    int ans= x * partialAns;
    return ans;
}

int main(){

    int x=2;
    int n=4;

    cout<<power(x,n);
}
