/* WACP to check for prime */
#include<stdio.h>
#include<math.h>
void main()
{
int n, i,m=0,flag=0;
clrscr();
printf("\n enter the no to check prime");
scanf("%d",&n);
m=n\2;
for (i=2;i<m;i++)
}
if (n%i==0)
{
ptinrf("the given no is not prime");
flag=1;
break;
}
}
if (flag==0)
printf("the given no is prime")
getch();
}

output:
enter the no to check prime 6
the iven no is not prime,
enter the no to check prime 5
the given no is not prime.

