# PAT乙级测试点
PAT乙级测试点遇到情况总结，希望大家用精炼的语言把自己没有考虑到的情况继续补充，也可以在别人已经写过的题目里继续补充。
<br>
用表格形式整合，保证题号的顺序是从小到大的。
<br>
如果感觉在github里补充较麻烦，也可以在协作文档中补充，我会同步到github处。
<br>
链接：<a href="https://yiqixie.com/d/home/fcACe6xZ2aroPxFQrQZ05Cw32" target="_blank">协作文档</a>

题号|题目|测试点问题补充
-|-|-
1003|我要通过！|只能出现'P'、'A'、'T'；'P'、'T'只能出现一次；'A'出现次数大于0；'P'前面的A与'P'、'T'之间的A数量之积等于'T'后面的A的数量。条件解读：https://blog.csdn.net/qq_40612211/article/details/96766886
1019|数字黑洞|题目要求输入数据是小于10000，即有可能输入一个一位数，两位数，注意补零；相减时也有可能不是4位数
1020|月饼|库存和总价都有可能是浮点数；需求有可能大于库存
1027|打印沙漏|符号的右半边没有空格
1028|人口普查|当有效值为0时，只输出0，不输出姓名，姓名为空也是不可以的
1030|完美数列|容易想当然的认为，最小值m应该取整个数列的最小值，这样的想法有问题，因为要求使数列中最大值M大于等于最小值的p倍，找出最长数列
1040|有几个PAT|X代表长度大于等于0的字符串，只要形如PXAXT，相对顺序是这样的，就可以组成
1044|火星数字|13的整数倍时，后面的输出不带'tret'
1045|快速排序|测试点2不通过的话，是没有主元的情况，不仅要输出0，而且还要输出下一行，只不过下一行为空。

