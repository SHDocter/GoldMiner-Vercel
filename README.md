# 黄金矿工LiveServer版

## 开发日志

### 2022-05-29

- 实现了游戏界面更改时间和页面切换功能
- 优化界面切换逻辑，将score_number的resize整合到render里面
- 绘制商店界面技能价格背景
- 绘制商店技能的价格
- 优化game_background的resize逻辑，并更改game_map里的resize

### 2022-05-28

- 加入tnt炸毁矿物的动画
- 编写tnt爆炸逻辑，实现了连爆
- 解决了tnt无法炸掉所有矿物的bug
- 调整了矿物的质量参数
- 完成了商店顶端的数字栏
- 完成了商店的下一关按钮
- 成功绘制了技能图标的在售和售出样式！
- 实现了点击购买技能的逻辑和页面展示
- 解决了canvas聚焦和键盘监听事件绑定失败的bug
![](https://picgo-yangqing.oss-cn-hangzhou.aliyuncs.com/img/20220528215608.png)
![](https://picgo-yangqing.oss-cn-hangzhou.aliyuncs.com/img/20220528215443.png)
![](https://picgo-yangqing.oss-cn-hangzhou.aliyuncs.com/img/202205282157627.jpg)

### 2022-05-27

- 优化了抓取逻辑
- 删除了一些不必要的代码
- 绘制炸弹图标和旁边的炸弹数量
- 实现炸弹炸毁钩子上矿物功能
![](https://picgo-yangqing.oss-cn-hangzhou.aliyuncs.com/img/20220528102132.png)

### 2022-05-26

- 实现数字跟随金钱自动更改
- 加入钩子抓住东西的图片和位置
- 可以根据绳子长度绘制绳子图片
- 绘制卷线器
- 绘制矿物图标、位置、碰撞体积
- 编写随机生成矿物位置的函数
![](https://picgo-yangqing.oss-cn-hangzhou.aliyuncs.com/img/20220526224449.png)

### 2022-05-25

- 实现大金块类
- 优化钩子操作
- 编写游戏背景类
- 绘制游戏背景图片
- 绘制图标和数字槽
- 绘制数字
![](https://picgo-yangqing.oss-cn-hangzhou.aliyuncs.com/img/20220526101304.png)

### 2022-05-24

- 删除多余的静态文件，修改appid
- 实现玩家类
- 实现钩子类
- 实现金矿基类
![](https://picgo-yangqing.oss-cn-hangzhou.aliyuncs.com/img/20220524203558.png)

### 2022-05-23

- 迁移游戏模板