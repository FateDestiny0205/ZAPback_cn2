---
icon: joystick
---

# 标签RTP调控

**1.功能说明**

可以通过用户标签对特定类型的用户进行RTP调控的功能

**2.筛选与查询功能**

<figure><img src="../../.gitbook/assets/image (177).png" alt=""><figcaption></figcaption></figure>

可按国家和运营商进行筛选

**3.列表字段**

（1）ID：调控ID

（2）运营商：归属运营商

（3）用户标签：该调控对应的单个/多个用户标签

（4）彩金RTP调控值（杀率调控）：该调控值作用于「打码通用配置」里设定的杀率彩金部分。举例：如果某活动的彩金杀率为 50%，则玩家获得的彩金中有 50% 将受“杀率调控RTP”限制。如果没有配置 → 不进行调控。如果存在多条规则且有重叠 → 取最低的RTP值进行调控。![](file:///C:/Users/Administrator/AppData/Local/Temp/msohtmlclip1/01/clip_image004.jpg)![](file:///C:/Users/Administrator/AppData/Local/Temp/msohtmlclip1/01/clip_image006.jpg)

<figure><img src="../../.gitbook/assets/image (178).png" alt=""><figcaption></figcaption></figure>

<div align="left"><figure><img src="../../.gitbook/assets/image (180).png" alt="" width="375"><figcaption></figcaption></figure></div>

（5）彩金RTP调控值（非杀率调控）：该调控值作用于「打码通用配置」中非杀率彩金部分。调控顺序：先执行杀率调控；剩余彩金再由“非杀率调控RTP”限制。特殊情况：如果“杀率调控”未配置，而“非杀率调控”已配置 → 所有彩金都按“非杀率调控RTP”执行。

（6）游戏最高倍数：即执行调控时玩家彩金部分的游戏最高倍数

（7）状态：该调控的开关状态

（8）操作人：此调控的操作人

（9）操作时间：此调控的操作时间

（10）操作：编辑或者删除此调控

a.运营商：归属运营商

b.用户标签：该调控对应的单个/多个用户标签

c.RTP杀率调控：该调控值作用于「打码通用配置」里设定的杀率彩金部分。举例：如果某活动的彩金杀率为 50%，则玩家获得的彩金中有 50% 将受“杀率调控RTP”限制。如果没有配置 → 不进行调控。如果存在多条规则且有重叠 → 取最低的RTP值进行调控。

d.RTP非杀率调控：该调控值作用于「打码通用配置」中非杀率彩金部分。调控顺序：先执行杀率调控；剩余彩金再由“非杀率调控RTP”限制。特殊情况：如果“杀率调控”未配置，而“非杀率调控”已配置 → 所有彩金都按“非杀率调控RTP”执行。

e.游戏最高倍数：即执行调控时玩家彩金部分的游戏最高倍数

f.状态：该调控的开关状态
