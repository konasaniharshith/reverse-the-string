# reverse-the-string
done by harshith
#include<stdio.h>
#include<conio.h>
int main()
{
    char s[20],a[20];
    int i,j,count=0;
    printf("Enter your string\n");
    gets(s);
    while(s[count!]='\0')
      count++;
      j=count-1;
      for(i=0;i<count;i++)
      {
         a[i]=s[j];
         j--;
      }
      a[i]='\0';
      printf("%s\n",a);
      return 0;
}
input : Mycaptain
output : niatpacyM
