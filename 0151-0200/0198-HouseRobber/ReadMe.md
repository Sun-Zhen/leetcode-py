### 题目
* 你是一个专业的强盗，计划抢劫沿街的房屋。
* 每间房都藏有一定的现金，阻止你抢劫他们的唯一的制约因素就是相邻的房屋有保安系统连接，
* 如果两间相邻的房屋在同一晚上被闯入，它会自动联系警方。
* 给定一个代表每个房屋的金额的非负整数列表，确定你可以在没有提醒警方的情况下抢劫的最高金额。

### 思路
#### DP
* 状态转移方程 dp[i] = max(dp[i - 1], dp[i - 2] + num[i - 1])
* dp[i]表示打劫到第i间房屋时累计取得的金钱最大值