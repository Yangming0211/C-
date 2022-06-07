# C-
C程序语言的一些代码记录
//============最大公约数的计算=======
#include<stdio.h>

int main()
{
	int m = 0;
	int n = 0;
	int r = 0;
	scanf_s("%d%d", &m, &n);
	while (m % n)
	{
		r = m % n;
		m = n;
		n = r;
	}
	printf("%d\n", n);
	return 0;
}
