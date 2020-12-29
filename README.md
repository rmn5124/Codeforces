# Codeforces-Ladder-A

//way too long word
//https://codeforces.com/problemset/problem/71/A

#include<bits/stdc++.h>
using namespace std;
void res(string s){
    int n=s.size();
    int count=0;
    for(int i=1;i<n-1;i++)
    count++;
    cout<<s[0]<<count<<s[n-1]<<endl;
}
int main(){
int n;
cin>>n;
string s;
for(int i=0;i<n;i++){
    cin>>s;
    if(s.size()>10){
        res(s);}
        else{
            cout<<s<<endl;}
        
    }
 
    return 0;
    }
