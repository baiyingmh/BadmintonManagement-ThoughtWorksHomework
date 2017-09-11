## BadmintonManagement-ThoughtWorksHomework:羽毛球场管理
### 功能（完成题目基本要求,满足给出的测试用例）:
- 输入预订信息预定一个羽毛球场地（格式：{用用户ID} {预订日日期 yyyy-MM-dd} {预订时间段 HH:mm~HH:mm} {场地}例如：'U001 2016-06-02 22:00~22:00 A'）
- 输入取消预订信息取消预定一个羽毛球场地(格式：{用用户ID} {预订日日期 yyyy-MM-dd} {预订时间段 HH:mm~HH:mm} {场地} {取消标记}例如：'U001 2016-06-02 22:00~22:00 A C')
- 输入汇总信息的命令打印羽毛球场的预定,小计,总计等信息(汇总信息的命令是空格：' ')

### 需执行以下命令运行程序（严格按照顺序执行）
1. 运行：`git clone git@github.com:baiying1314/BadmintonManagement-ThoughtWorksHomework.git` 将代码下载到本地
2. 运行：`npm install`安装需要的模块
3. 运行：`npm test`运行测试代码
4. 运行：`npm start`运行程序
5. 输入信息进行相应操作

### 做题过程
1. 理解题目要求,捋顺思路
2. 纸上画图画出大概流程以及各种情况
3. 设计数据结构,确定存储模式（存于json文件中）
4. 设计入口文件，初始化数据
5. 根据第２条的图对不同的情况进行相应处理
6. 写测试并进行调试
7. 优化代码（抽取变量和函数）


### 做题时间
- 预计用时:三天
- 实际用时：两天半

### 反思总结
- 做的好的地方：一开始的画图使得思路比较清晰，对于数据结构以及存储模式的设计使得后边做得比较流畅
- 不好的地方：本来是想以测试先行的原则来写的,但感觉思路比较模糊,就先写了实现代码
- 过程中遇到的的问题：对于一些异步的函数处理时问题比较多（尤其在测试的时候），部分改成了同步函数，后续会继续研究这部分，尽量找出更好的解决方案