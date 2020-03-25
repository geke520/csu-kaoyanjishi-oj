# 中南大学历年机试解答

使用语言：c++

## 试题

### 2013

[回文串问题](/2013/palindrome_string.cpp)

[水仙花数](/2013/num_narciscus.cpp)

[安全密码](/2013/safe_password.cpp)

[最少钱币数](/2013/fewest_money.cpp)

[惠民工程](/2013/benefit_project.cpp)

### 2014

[成绩转换](/2014/grades_translation.cpp)

[最大连续子序列](/2014/max_continued_sub_seq.cpp)

[破译密码1](/2014/passwd_decode.cpp)  

[破译密码2](/2014/passwd_decode_2.cpp)

[安全路径](/2014/safe_path.cpp)  

[平方和与立方和](/2014/square_cube_sum.cpp)

### 2015

[电子地图](2015/e_map.cpp)

[容易的题](2015/easy_question.cpp)

[数字](2015/number.cpp)

[奇怪的餐厅](2015/strange_canteen.cpp)

[防水堤坝](2015/strange_dam.cpp)

### 2016

[序列求平均](2016/average_sequence.cpp)

[加油站](2016/gas_station.cpp)

[堆石子](2016/rock_fill.cpp)

[士兵排阵](2016/soldier_rank.cpp)

[士兵排阵2](2016/soldier_rank2.cpp)

[第几天](2016/which_day.cpp)

## 注意事项

1. 算法格式错误可能是因为在有多个输出情况下，答案要求一一及时输出，而不是统一输出。见2014年破译密码1。

2. 算法可能因为精度答案出错，如float与double；可能因为发生溢出而答案出错。

3. `memeset()`是按字节赋值的，对于非字符类型的初始化：

```c++ 
int a[10];
memset(a, 0, sizeof(a)); // a[0] = 0x00000000
memset(a, 1, sizeof(a)); // a[0] = 0x01010101
memset(a, 127, sizeof(a)); // a[0] = 0x7f7f7f7f
memset(a, 255, sizeof(a)); // a[0] = 0xffffffff = -1
```