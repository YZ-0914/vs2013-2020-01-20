# vs2013-2020-01-20
#define _CRT_SECURE_NO_WARNINGS 1
#include<stdio.h>
#include<math.h>
//乘法口诀表
//在屏幕上输出9^9乘法口诀表
int main()
{
	int i = 0;
	//确定打印9行
	for (i = 1; i <= 9; i++)
	{
		printf("%d%d=%-2d", i, j, i*j);
	}
	printf("\n");
	return 0;
}

////求最大值
////求10个整数中最大值
//int main()
//{
//	int arr[] = { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 };
//	int max = arr[0];//最大值
//	for (i = 1; i < sz; i++)
//	{
//		if (arr[i]>max)
//		{
//			max = arr[i];
//		}
//	}
//	printf("max=%d\n", max);
//	return 0;
//}

////数9的个数
////编写程序数一下1到100的所有整数中出现多少个数字9
//int main()
//{
//	int i = 0;
//	int count = 0;
//	for (i = 1; i <= 100; i++)
//	{
//		if (i % 10 == 9)
//			count++;
//		if (i / 10 == 9)
//			count++;
//	}
//	//9 19 29 39 49 59 69 79 89 99-10
//	//90 91 92 93 94 95 96 97 98 99-10
//	printf("count=%d\n", count);
//	return 0;
//}

////打印素数
////写一个代码打印100~200之间的素数
//int main()
//{
//	int i = 0;
//	int count = 0;
//	//sqrt-开平方的数学库函数
//	for (i = 100; i <= 200; i++)
//	{
//		int j = 0;
//		for (j = 2; j <= sqrt(i); j++)
//		{
//			if (i%j == 0)
//			{
//				break;
//			}
//		}
//		if (j > sqrt(i))
//		{
//			count++;
//			printf("%d", i);
//		}
//	}
//	printf("%d", count);
//}

//int main()
//{
//	int i = 0;
//	int count = 0;
//	for (i = 100; i <= 200; i++)
//	{
//		//判读i是否为素数
//		//素数判断的规则
//		//1.试除法
//		//产生2->i-1
//		int j = 0;
//		for (j = 2; j < 1; j++)
//		{
//			if (i%j == 0)
//			{
//				break;
//			}
//		}
//		if (j == i)
//		{
//			count++;
//			printf("%d", i);
//		}
//	}
//	printf("\ncount=%d\n", count);
//	return 0;
//}

////打印闰年
////打印1000到2000年之间的闰年
//int main()
//{
//	int year = 0;
//	for (year = 1000; year <= 2000; year++)
//	{
//		//判断year是否为闰年
//		//1.能被4整除并且不能被100整除是闰年
//		//2.能被400整除
//		int count = 0;
//			if ((year % 4 == 0) && (year % 100 != 0)||(year%400==0))
//			{
//			printf("%d", year);
//			count++;
//			}
//		
//	}
//	return 0;
//}

////最大公约数
////给定两个数，求这两个数的最大公约数
////辗转相除法
//int main()
//{
//	int m = 24;
//	int n = 18;
//	int r = 0;
//	scanf("%d%d", &m, &n);
//	while (r = m%n)
//	{
//		m = n;
//		n = r;
//	}
//	printf("%d\n", n);
//	return 0;
//}

////打印3的倍数的数
////写一个代码打印1-100之间所有3的倍数的数字
//int main()
//{
//	int i = 0;
//	int count = 0;
//	for (i = 1; i <= 100;i++)
//		if (i % 3 == 0)
//		{
//		printf("%d\n", i);
//		count++;
//		}
//	printf("\ncount=%d\n", count);
//	return 0;
//}

////从大到小输出
////写代码将三个数按从大到小输出
//int main()
//{
//	int a = 0;
//	int b = 0;
//	int c = 0;
//	scanf("%d %d %d", &a, &b, &c);
//	if (a < b)
//	{
//		int d = 0;
//		d = b;
//		b = a;
//		a = d;
//	}
//	if (a < c)
//	{
//		int d = 0;
//		d = c;
//		c = a;
//		a = d;
//	}
//	if (b < c)
//	{
//		int d= 0;
//		d = c;
//		c = b;
//		b = d;
//	}
//	printf("%d %d %d ", a, b, c);
//	return 0;
//}

//int main()
//{
//	int x = 3;
//	int y = 3;
//	switch (x % 2)
//	{
//	case 1:
//		switch (y)
//		{
//		case 0:
//			printf("first");
//		case 1:
//			printf("good");
//			break;
//		default:printf("hello");
//		}
//	case 2:
//		printf("third");
//	}
//		
//	return 0;
//}

//int func(int a)
//{
//	int b;
//	switch (a)
//	{
//	case 1:b = 30;
//	case 2:b = 20;
//	case 3:b = 16;
//	default:b = 0;
//	}
//	return b;
//}

//int main()
//{
//	int i = 0;
//	for (i = 0; i < 10; i++)
//	{
//		if (i = 5)
//			printf("%d\n", i);
//	}
//	return 0;
//}

//int sum(int a)
//{
//	int c = 0;
//	static int b = 3;
//	c += 1;
//	b += 2;
//	return(a + b + c);
//}

//int main()
//{
//	int i = 0;
//	int a = 2;
//	for (i = 0; i < 5; i++)
//	{
//		printf("%d", sum(a));
//	}
//	return 0;
//}

//int main()
//{
//	int i = 0;
//	int count = 0;
//	for (i = 101; i <= 200; i += 2)
//	{
//		int j = 0;
//		i = i*1.0;
//		for (j = 2; j < sqrt(i); j++)
//		{
//			if (i%j==0)
//			{
//				break;
//			}
//		}
//		if (j>sqrt(i))
//		{
//			count++;
//			printf("%d", i);
//		}
//	}
//	printf("\ncount=%d\n", count);
//	return 0;
//}

//int main()
//{
//	int i = 0;
//	int count = 0;
//	for (i = 100; i <= 200; i++)
//	{
//		int j = 0;
//		i = i*1.0;
//		for (j = 2; j <= sqrt(i); j++)
//		{
//			if (i%j == 0)
//			{
//				break;
//			}
//		}
//		if (j > sqrt(i))
//		{
//			count++;
//			printf("%d\n", i);
//		}
//	}
//	printf("\ncount=%d\n", count);
//	return 0;
//}
