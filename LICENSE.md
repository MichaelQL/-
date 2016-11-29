#include <stdio.h>

int main()

{
	int hour1,hour2,minute1,minute2;
	
	scanf("%d %d",hour1,minute1);
	scanf("%d %d",hour2,minute2);

    int time1=hour1*60+minute1;

    int time2=hour2*60+minute2;
	
	int t=time2-time1;
	printf("%d",t);
	
}
