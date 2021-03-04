# Codeforces
//https://codeforces.com/problemset/problem/1487/A

#include<bits/stdc++.h>
using namespace std;
#define tst               long t;cin>>t;while(t--)
#define rep(i,a,n)         for(int i=a;i<n;i++)
#define ull               unsigned long long int
#define ll                long long int
 
int main(){
   ios_base::sync_with_stdio(false);
   cin.tie(NULL);cout.tie(NULL);
 tst{
ll n;cin>>n;
  
	    vector<ll>res(n);
	    for(ll i=0;i<n;i++){
	        cin>>res[i];
	    }
	    ll mn = *min_element(res.begin(),res.end());
	    ll cnt= 0;
	    for(ll i=0;i<n;i++){
	        if(res[i]==mn){cnt++;}
	    }
	    cout<<res.size()-cnt<<endl;
	}
return 0;   
}
