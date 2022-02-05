# CSES-Intro--2
Missing Number Solution 

#include<bits/stdc++.h>
using namespace std;
 
int main(){
    long long int n;
    cin>>n;
    int s=0;
    for (int i = 0; i < n-1; i++)
    {
        int h;
        cin>>h;
        s=s+h;
    }
    int d=n*(n+1)/2;
    cout<<d-s<<endl;
return 0;
}
