## LeetCode
>* leetcode的python版本实现，有自己的想法，也有参考别人的博客等资料
>* 参考博文资料有：
>  * http://bookshadow.com/leetcode/
>  * https://www.cnblogs.com/daoluanxiaozi/p/longest-palindromic-substring.html
>  * http://www.cnblogs.com/grandyang/p/4606334.html
>  * https://blog.csdn.net/m0_37889928/article/details/79809808
>* 感谢各种神様的博文分享
>* 预期目标是所有题做完，并且尽可能给出别的想法
>* 注：简单:中等:困难=1:2:1


## 算法分类
#### 动态规划
* 个人理解有两点
  - 找到『状态』的定义
  - 找到一个合理的『状态』转移方程
* **相关题目**
  - 0005 最长回文字符串
  - 0198 打家劫舍
  - 0152 乘积最大的连续子序列
  - 0746 使用最小花费爬楼梯
  - 0303 查询-区域和

#### 树相关
* 0100

#### 贪心算法
* 

#### 回溯算法
* 小结
  1.找到选择
  2.限制条件，即选择操作在此条件下才进行
  3.结束
* 0784 字母大小全排列


## 典型系列问题
#### 回文系列
> * 相关题目
>  * 0005 最长回文字符串
>  * 0234 判断回文链表
> * 注：奇回文与偶回文
* 解法1:以每个字符为中心，向两边扩散寻找回文串
  * 时间复杂度为O(n<sup>2</sup>)
* 解法2:动态规划
  * 找到状态转移方程
  * 定义状态
* 解法3:马拉车算法(Manacher)
  * 对于半径的理解
  * 对于中心点的切换


#### 范围求和问题
* 0370,0598

#### 最长子序列 Longest Common Subsequence (LCS)
> https://blog.csdn.net/ljyljyok/article/details/77905681
> https://blog.csdn.net/jc69186918/article/details/52851410

#### 最长连续子串(连续)

#### 数组操作
* 双指针
  * 0011 盛最多水的容器
  * 两/三/四数之和一类(K sum problem)
    - http://www.cnblogs.com/tenosdoit/p/3647244.html
    - http://www.cnblogs.com/tenosdoit/p/3649607.html
    - 0001,0015,0016,0018,0167,0170,0653
* "排列"系列问题（全排列，下一个排列）
  * 0077
  
  

#### 链表操作
> https://blog.csdn.net/qq_26768741/article/details/51635987


* 翻转类
  * 单纯翻转
    - 0206
  * 分段翻转
  * 链表对折

