#include <stdio.h> 
#include <stdlib.h> 

int a(int a) { 
int aa=0; 
a: if (!a) goto aa; 
a/=10; 
aa++; 
goto a; 
aa: return aa; 
} 

int aa(int aa) { 
int aaa=2,aaaa=0,aaaaa=a(aa),aaaaaa=0; 
a: if (!(aa%aaa)) { aaaa++; aa/=aaa; goto a;} 
if (!aaaa) { aaa++; goto a; } 
if (aaaa>1) aaaaaa+=a(aaaa); 
aaaaaa+=a(aaa); 
if (aa==1 || aaaaaa>=aaaaa) goto aa; 
aaa++; 
aaaa=0; 
goto a; 
aa: if (aaaaa>aaaaaa) return 1; 
return 0; 
} 

int main () { 
int aaa,aaaa=2; 
printf("Enter n: "); 
scanf("%d",&aaa); 
a: if (aa(aaaa)) printf("%d\n",aaaa); 
if (++aaaa<aaa) goto a; 
}
