# codeC
#include <stdio.h>
#include <string.h>
#include <ctype.h>
#include <stdlib.h>
void chuanhoa(char c[]){
  c[0]=toupper(c[0]);
  for(int i=1; i<strlen(a); i++)
    c[i]=tolower(c[i]);
}
int main(){
int t;
scanf("%d", &t);
getchar();
while(t--){
  char c[1000], a[20][50];
  int n=0; 
  gets(c);
  char *token=strtok(c, " ");
  while(token!=NULL){
    token=strtok("NULL, " ");
  }
  for(int i=0; i<n; i++) {
    chuanhoa(a[i]);
    print("%s ", a[i]);
  }
  printf("\n");
  }
}
