# 搜索添加联系人
`android逆向与安全`

---



# 前言

## A.流程

- [01.流程试玩]()
- [02.需求分析与拆解]()
- [03.逆向分析与学习过程]()
- [04.业务逻辑初步实现]()
- [05.实现代码自我测试]()
- [06.细节更进一步分析]()
- [07.性能考虑]()
- [08.用户行为模拟]()
- [09.合并到大code]()
- [10.真实环境测试，以及极限性能测试]()
---

# 03.整个业务逻辑分析(详见本地笔记)

# 其余细节学习

- 分别使用微信号、QQ号、手机号搜索
- 第一步搜不到联系人的情况处理
- 对方未开启好友验证的情况
- 开启好友验证的情况
- 并支持添加好友请求信息，以及朋友圈可见等参数设置
- 对方没有删你的情况处理
- 如果已经是好友的情况处理
- 自己搜索自己的情况处理
- 黑名单的情况，又分为
    - 你把对方添加黑名单的情况
    - 对方把你加黑名单的情况
    - 添加成功之后微信UI的更新情况

