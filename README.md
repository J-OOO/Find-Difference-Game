# 找茬游戏，Java Swing编程

## 功能介绍

1.挑战模式：总时长150秒，最多8关，每关限时30秒，或找出五处不同后即刻进入下一关。破纪录会写入排行榜

2.选关模式：玩家自己选择关卡

3.支持玩家自己导入关卡

4.新增排行榜

## 实现原理

每个关卡包含两张图片和五处不同点的坐标，当玩家点击鼠标时获取点击处的坐标，计算该坐标和答案坐标的距离是否小于某个范围，是则说明玩家找到一个不同处，否则说明查找错误。
