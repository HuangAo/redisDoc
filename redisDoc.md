# 1.redis数据类型

redis有5大基本类型和3种特殊类型

5大基本数据类型：

1. <font color=red>String (字符串)</font>

   可以是字符串（简单的字符串、复杂的字符串（例如JSON、XML））、数字（整数、浮点数），甚至是二进制（图片、音频、视频），但是值最大不能超过512MB

2. <font color=red>hash</font>

   ![image-20210406160347455.png](redisDoc.assets/image-20210406160347455.png)

   使用场景：存储用户信息

3. <font color=red>sets</font>

4. <font color=red>sorted sets</font>

5. <font color=red>list</font>

3种特殊数据类型：

1. GEO (地理位置)
2. hyperLogLog (基数统计算法) -- 一种不精确的去重计数方案
3. bitmaps (位图) -- 打卡签到