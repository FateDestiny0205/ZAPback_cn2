---
icon: display
---

# 弹窗策略配置

**1.功能说明**

配置弹窗的弹出策略，针对不同标签的用户，可以配置不同的弹出策略

**2.筛选与查询功能**

<figure><img src="../../.gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>

2.1运营商

选择某个运营商的弹窗策略进行查询

2.2策略状态

策略是开启还是关闭，还是全部

2.3弹窗链路

弹窗是单链路还是多链路，还是全部  &#x20;

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">链路模式</td><td valign="top">含义</td><td valign="top">弹窗逻辑结构</td><td valign="top">典型用途</td></tr><tr><td valign="top">单链路</td><td valign="top">一条固定路径</td><td valign="top">A → B → C</td><td valign="top">固定流程类提示、引导</td></tr><tr><td valign="top">多链路</td><td valign="top">多条条件分支路径</td><td valign="top">A → (B/C/D)</td><td valign="top">根据不同行为展示不同弹窗</td></tr></tbody></table>

**3.列表字段**

（1）ID：弹窗策略ID

（2）运营商：归属运营商

（3）策略标题：弹窗策略的标题

（4）用户标签：策略针对的用户标签

（5）策略权重：如果有重复标签，同时满足多个弹窗策略触发条件时，触发权重最高的那个

（6）排序：后台弹窗策略的排序

（7）弹窗链路类型：是单链路还是多链路

（8）弹窗链路详情：具体的链路触发详情

<div align="left"><figure><img src="../../.gitbook/assets/image (50).png" alt="" width="254"><figcaption></figcaption></figure></div>

（9）状态：目前的开关状态

（10）操作：编辑和删除目前的弹窗策略

**4.新增策略**

<div align="left"><figure><img src="../../.gitbook/assets/image (54).png" alt="" width="77"><figcaption></figcaption></figure></div>

点击新增策略按钮来新增策略

<div align="left"><figure><img src="../../.gitbook/assets/image (55).png" alt="" width="328"><figcaption></figcaption></figure></div>

1.运营商：归属运营商

2.策略排序：弹窗策略在后台列表的排序

3.用户标签：弹窗策略对哪些用户标签生效，可单/多选

4.策略标题：弹窗策略的标题

5.策略权重：弹窗策略的权重，同时满足多个弹窗策略触发条件时，触发权重最高的那个

6.策略状态：弹窗策略的开启或关闭状态

7.策略路径：配置具体的弹窗策略

（1）单个弹窗设置

<figure><img src="../../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure>

a.关联首个弹窗ID：与弹窗配置中的哪个弹窗关联

b.当前弹窗展示位置：弹窗在哪个页面弹出

c.首个弹窗每日展示次数：首个弹窗的展示次数，如果次数已达到配置值，则执行下一个弹窗逻辑

d.启动应用就弹：是否在启动应用时就弹出，启动应用就弹也会计入首个弹窗每日展示次数

（2）新增弹窗

<div align="left"><figure><img src="../../.gitbook/assets/image (57).png" alt="" width="81"><figcaption></figcaption></figure></div>

点击新增下一弹窗按钮，可设置下一弹窗的逻辑

<div align="left"><figure><img src="../../.gitbook/assets/image (58).png" alt="" width="289"><figcaption></figcaption></figure></div>

<div align="left"><figure><img src="../../.gitbook/assets/image (59).png" alt="" width="375"><figcaption></figcaption></figure></div>

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">链路模式</td><td valign="top">含义</td><td valign="top">弹窗逻辑结构</td><td valign="top">典型用途</td></tr><tr><td valign="top">单链路</td><td valign="top">一条固定路径</td><td valign="top">A → B → C</td><td valign="top">固定流程类提示、引导</td></tr><tr><td valign="top">多链路</td><td valign="top">多条条件分支路径</td><td valign="top">A → (B/C/D)</td><td valign="top">根据不同行为展示不同弹窗</td></tr></tbody></table>

（3）第二个及之后的弹窗设置

<figure><img src="../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

a.第2个弹窗展示条件：参与上个弹窗活动，还是上个弹窗关闭次数（需要后面配置具体次数），还是上个弹窗弹出次数（需要后面配置具体次数）

<div align="left"><figure><img src="../../.gitbook/assets/image (61).png" alt="" width="252"><figcaption></figcaption></figure></div>

<div align="left"><figure><img src="../../.gitbook/assets/image (62).png" alt="" width="375"><figcaption></figcaption></figure></div>

<div align="left"><figure><img src="../../.gitbook/assets/image (63).png" alt="" width="375"><figcaption></figcaption></figure></div>

b.关联第2个弹窗ID：与弹窗配置中的哪个弹窗关联

c.当前弹窗展示位置：弹窗在哪个页面弹出

d.第2个弹窗每日展示次数：首个弹窗的展示次数，如果次数已达到配置值，则执行下一个弹窗逻辑

e.与上个弹窗时间间隔：关闭上个弹窗N秒后，执行下个弹窗展示逻辑

（4）删除当前弹窗

<div align="left"><figure><img src="../../.gitbook/assets/image (64).png" alt="" width="85"><figcaption></figcaption></figure></div>

可点击删除当前弹窗删除当前弹窗
