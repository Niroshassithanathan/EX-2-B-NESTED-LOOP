# EX-2-B-NESTED-LOOP
## AIM :
Write a C program for the following pattern:
```
1
2 6
3 7 10
```
## ALGORITHAM :
1.Start

2.Declare variables to control the pattern, including i, j, and count.

3.Initialize count to 1.

4.Use a nested loop structure to control the pattern:

5.Move to the next row.

6.End.
## PROGRAM :
```#include<stdio.h>
int main(){
for(int
i=1;i<=3;i++){int
x=4,t=i;
printf("%d ",i);
for(int j=1;j<i;j++){
t+=x;
printf("%d ",t);
x--;
}
printf("\n");
}
}```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-2-B-NESTED-LOOP/assets/121418437/c3659322-8ad1-44ee-bf7a-55b9c0cc2c1c)
## RESULT :
Thus , The C program has been executed successfully.
