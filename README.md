# Hello-MCS-Program
Learning about Git with the help of our seniors via MCS
Hii guys!!
This is Kishore here..landed on feb 7th 2000..basically an introvert but not so nowadays..
Learning a lo of life lessons nowadays!!
BASICS OF IMPLEMENTATION
  #include<iostream>
using namespace std;
int main()
{
    string s;
    cin>>s;
    int len=s.length();
    int a=0,b=0,c=0,d=0,e=0,f=0,g=0,h=0,k=0,j=0;
    for(int i=0;i<len;i++)
    {
    if(s[i]=='0')
        a++;
    if(s[i]=='1')
    b++;
    if(s[i]=='2')
    c++;
    if(s[i]=='3')
    d++;
    if(s[i]=='4')
    e++;
    if(s[i]=='5')
    f++;
    if(s[i]=='6')
    g++;
    if(s[i]=='7')
    h++;
    if(s[i]=='8')
    k++;
    if(s[i]=='9')
    j++;
    }
    cout<<"0 "<<a<<"\n";
    cout<<"1 "<<b<<"\n";
    cout<<"2 "<<c<<"\n";
    cout<<"3 "<<d<<"\n";
    cout<<"4 "<<e<<"\n";
    cout<<"5 "<<f<<"\n";
    cout<<"6 "<<g<<"\n";
    cout<<"7 "<<h<<"\n";
    cout<<"8 "<<k<<"\n";
    cout<<"9 "<<j<<"\n";
}
ARRAY PROGRAM
                    #include<iostream>
using namespace std;
int main()
{
  int n,*p;
  cin>>n;
  if(n<=100)
  p=new int[n];
  for(int i=0;i<n;i++)
  cin>>p[i];
  for(int i=n-1;i>=0;i--)
  cout<<p[i]<<"\n";
}
