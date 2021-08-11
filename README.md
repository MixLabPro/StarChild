# 星星的孩子 - 一款为孤独症孩子设计的聊天机器人游戏

孤独症儿童是目前常常被忽视的一类群体。他们有着类似性格内向的特征，实际却受着广泛性发育障碍的折磨。

### 项目背景

这类儿童在与人交往时存在着沟通障碍，其特点表现在：

- 社交交流差，互动障碍明显
- 认知能力有限，被动认知
- 兴趣狭窄，重复刻板，缺乏变化和想象力
- 固有行为习惯和行为方式，难以适应新环境

他们的这些症状在经过培训后往往可以得到改善，但却不能完全根治。我们应该更加关注这类群体的需求，为他们提供更多的关爱。

目前常用的教学方法为ABA应用行为分析，针对以下两方面能力进行培养：

- 感知能力
- 思维运用能力

具体训练内容有：

- 物品归类
- 指令动作
- 寻找丢失物
- 记事能力
- 请求帮助
- 利用所学

### 游戏玩法

![ezgif-1-8de7005005e4](https://user-images.githubusercontent.com/60060750/128956571-dcd6b205-7784-4c19-9ba6-695b703f5ca1.gif)

(观看完整版[B站视频](https://www.bilibili.com/video/BV1hM4y157e3))

出于对通用性设计的考虑，我们选择了同样适用于普通儿童教育的认知学提高角度进行以下设计：

1. 从三种基本图形（圆，正方，正三角）中随机抽取，机器人动图展示并以抽奖形式定格其中一种图形
2. 用户根据收到的图形拍取其认为相似的真实物体发送给机器人
3. 收到回复后机器人开始进行判断，根据图片匹配度提供回复
4. 用户选择结束游戏/再来一局

儿童根据所收获的星星可以兑换更多图形模板进行后续的匹配度游戏，也可以在社区与其他小朋友进行PK。

## 技术文档

ToDo: one-line startup command, but core codes are under `/Wechaty` and `/CVModule` subdirectories for reviewing.
