# WH-01-
 #//Area Triangle Circle , Square
//---------------------------------------------------------------------------------------------------------
#include<stdio.h>
#include<math.h>

int main(){
	float hight,base,radius,side;
	float AswT,AswC,AswS;
	
	printf("-------Triangle---------\n");
	printf("Triangle Area Calculator\n");
	printf("Enter Hight :");
	scanf("%f",&hight);
	printf("Enter Base :");
	scanf("%f",&base);
	AswT=(hight*base)*1/2;
	printf("Area of Triangle = %.2f\n",AswT);
	
	printf("-------Circle---------\n");
	printf("Triangle Area Calculator\n");
	printf("Enter Radius :");
	scanf("%f",&radius);
	AswC = (radius*radius)*M_PI;
	printf("Area of Triangle = %.2f\n",AswC);
	
	printf("-------Square---------\n");
	printf("Triangle Area Calculator\n");
	printf("Enter Side :");
	scanf("%f",&side);
	AswS = side*side;
	printf("Area of Triangle = %.2f\n",AswS);
	 
	 //
	return 0;
}
