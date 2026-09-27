#include<stdio.h>
int m;
int max(int x,int y){
	if(x>y)
		m=x;
	else
		m=y;
	return m;//创建可以选择两个数中更大的一个数的函数
}
int main(){
	int n,i,z;
    printf("please enter how many numbers do u have\n");//输入n
	scanf("%d",&n);
	int x[n];
	for(i=0;i<n;i++){
        printf("please enter number %d\n",i+1);//输入每个数
		scanf ("%d",&x[i]);
    }
	for(i=0;i<n-1;i++)
		z=max(z,x[i]);
	printf("the max number is %d",z);//输出最大的一个
	return 0;
}