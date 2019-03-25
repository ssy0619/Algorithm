#include <stdio.h>
#pragma warning(disable:4996)

int Fibo(int n) {
	if (n == 1) { return 0; }
	else if (n == 2) { return 1; }
	else { return Fibo(n - 1) + Fibo(n - 2); }
}

int main() {
	
	int num;

	printf("자연수를 입력하시오:");
	scanf("%d", &num);
	
	for (int i = 1; i < num; i++) {
		printf("%d ", Fibo(i));
	}
	return 0;
}
