#include <stdio.h>
#include <math.h>

int l, w;
float s,p;

int main(void)
{
    printf("\nPPI计算器 v1.0.1\n");
    printf("==============\n");
    com();
    printf("\n结果：\nPPI为 %.0f。", p);
    getchar();
    getchar();
    return 0;
}
int com(void)
{
    printf("\n输入屏幕长、宽（单位：像素）及尺寸（单位：吋），\n输好每项请按回车键。\n");
    scanf("%d%d%e", &l, &w, &s);
    p = (float)sqrt(l*l + w*w) / s;
}
