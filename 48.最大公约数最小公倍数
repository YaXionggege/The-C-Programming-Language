#include<stdio.h>//头文件 
int main()//主函数 
{ 
   int m, n, num1, num2, temp;//定义整型变量 
   printf("请输入两个数：");//提示语句 
   scanf("%d %d", &num1, &num2);//键盘输入两个数 
   m=num1; //赋值 
   n=num2; //赋值 
   while(num2!=0) // 余数不为0，继续相除，直到余数为0 
   { 
       temp=num1%num2; 
       num1=num2; 
       num2=temp;
   }
   printf("最大公约数是：%d\n", num1);//输出最大公约数 
   printf("最小公倍数是：%d\n", m*n/num1);//输出最小公倍数 
}
