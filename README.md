# solved-coad

#include<iostream>
#include<cstdio>
#include<cstring>
using namespace std;
int main()
{
	char ch[105];
	gets(ch);
	int l=strlen(ch);
    int flag=0;
	char ch2[5][10]={"Danil","Olya", "Slava", "Ann","Nikita"};
    for(int i=0;i<l;i++)
    {
    	if(ch[i]=='D' && ch[i+1]=='a' && ch[i+2]=='n' && ch[i+3]=='i' && ch[i+4]=='l')
    	{
    		flag++;
		}
		if(ch[i]=='O' && ch[i+1]=='l' && ch[i+2]=='y' && ch[i+3]=='a')
    	{
    		flag++;
		}
    	if(ch[i]=='S' && ch[i+1]=='l' && ch[i+2]=='a' && ch[i+3]=='v' && ch[i+4]=='a')
    	{
    		flag++;
		}
		if(ch[i]=='A' && ch[i+1]=='n' && ch[i+2]=='n')
    	{
    		flag++;
		}
		if(ch[i]=='N' && ch[i+1]=='i' && ch[i+2]=='k' && ch[i+3]=='i' && ch[i+4]=='t' && ch[i+5]=='a')
    	{
    		flag++;
		}
    }  
    	if(flag==1)
    	{
    	cout<<"YES";
		}
		else{
	    cout<<"NO";
	   } 
	return 0;
}
