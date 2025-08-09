# missingnumber

#include<iostream>
#include<vector>
using namespace std;
int missingnumber(vector<int>&a, int n)
{
  int sum=(n*(n+1))/2;
  int s2=0;
  for(int i=0; i<n-1; i++)
  {
    s2+=a[i];
  }
  int missnumber=sum-s2;
  return missnumber;
}
