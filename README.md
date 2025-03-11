# C13
multiplication tables
#include<stdio.h>
int main()
{
	for(int i=1;i<=5;i++){
		for(int j=1;j<=5;j++){
			printf("%d X %d = %d \t",j,i,j*i);
	    }
	    printf("\n");
	}
	return 0;
}
