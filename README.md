//set-of-pair

#include <iostream>
#include<bits/stdc++.h>

using namespace std;

int main()
{ int n,m,k;
cin>>k;
  set<pair<int,int> >s;
   for(int i=0;i<k;i++)
   {   cin>>n>>m;
       s.insert(make_pair(n,m));
   }
   for(auto &j:s)
   {
       cout<<"("<<j.first<<" "<<j.second<<")"<<" ";
   }
    return 0;
}
