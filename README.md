# 100JUN-10869
STUDY
#include <stdio.h>

int main(void) {


	int A=0; //각각의 변수 설정
	int B=0;

	if (1 <= A && A <= 10000, 1 <= B && B <= 10000);//각각 A,B의 범위 설정
	{
	
		
			printf("A= "); //A의 정수 입력 부분
			scanf_s("%d", &A);

			printf("B= "); //B의 정수 입력 부분
			scanf_s("%d", &B);

			printf("두개의 합은 %d\n", A+B); //각각의 함수 출력값
			printf("두개의 차는 %d\n", A-B);
			printf("두개의 곱은 %d\n", A*B);
			printf("두개의 나누기 몫은 %d\n", A/B);
			printf("두게의 나눗셉 나머지는 %d\n", A%B);

    }

	
	return 0;

}
