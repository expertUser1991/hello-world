# hello-world
This is example named "hello world".

#include "iostream.h"
#include "algorithm.h"

using namespace std;

main() {
  //not ith bit
  freopen("in","r",stdin);
  int k,i; cin>>k>>i;
  cout<<(k ^ (1 << i))<<endl;
  return 1;
}
