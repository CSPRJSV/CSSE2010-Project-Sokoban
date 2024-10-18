# CSSE2010-Project-Sokoban
# ✅ 顶级大神，在线辅导 | 1v1 远程 | 助攻 | VIP 定制
# ✅ Lecture 同步辅导 | Assignment 专题辅导 | Test Prep | 挂科重修 One Last Chance
# 🚀 源头导师 | 科班出身 | TOEFL 115 | 非中介❌甩单转介绍 ！
# 🚀 职业道德 | 亲力亲为 | 全程手打原创 | 可 coaching oral interview 口试抽检 | 严厉拒绝❌一份多售
# 👉 Wechat: csprojhelp ⚠ 加我备注: github ⚠ Remark to Pass Your Friend Request: github 

## 【项目介绍】

用学校发的 ATmega324A MCU 和一系列外设 peripherals 实现经典的 Sokoban 推箱子游戏。有一个硬件的 LED Matrix 作为实体显示屏。项目由多个功能组成，按完成的功能得分。功能们被划分为 Tier A~C 三档，难度递增。每个档次得分有封顶 cap ，分别为 50+30+20 = 100。只求 pass 做到 50 分即可( Tier A 全部 )，性价比最高的是做到 75 分( Tier A + Tier B 部分 )。80 分以上需要完成 Tier C 功能，这些功能对游戏影响比较深， 每个都涉及到重构前面代码，肝帝学霸HD控专属。

## 【重点解析】

1. 第一件事永远永远不是写功能 ！！！ 先用简单代码确认硬件平台 setup ok and works ！！！
2. 棋盘布局和数组存储是反的！游戏坐标和数组坐标需要转换
3. 涉及闪烁的功能要注意对齐显示与熄灭周期的时间
4. Terminal Game Display 功能对性能有要求，不能无脑更新画面，需要实现增量更新，即只更新画面中有改动的部分
5. 实现Game Pause 功能时容易把计时部分弄乱，要想清楚逻辑
6. Tier B 的 Sound Effects 和 Joystick 功能需要连接新硬件，会与前面用的硬件 pin 脚冲突，需要重新规划布线

=======================================================

需要答疑或者 VIP 服务的童鞋左转我个人介绍，懂的都懂
