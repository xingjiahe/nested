# nested



//定义求来个两个数种的最大值

int max2(int num1,int num2)
{
    return  num1 > num2 ? num1 : num2;
}


//求三个数中的最大值

int max3(int num1,int num2,int num3)
{
    return max2(num1, num2) > num3 ? max2(num1, num2) : num3 ;

}


//求四个数种的最大值


int max4(int num1,int num2,int num3,int num4)
{
    return max3(num1, num2, num3) > num4 ? max3(num1,num2,num3): num4;

}
