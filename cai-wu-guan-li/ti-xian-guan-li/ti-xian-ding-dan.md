---
icon: coins
---

# 提现订单

**1. 界面位置**

* 左侧导航栏路径：财务管理 → 提现管理 → 提现订单。
* 功能说明:用于查看、筛选、导出及操作用户的提现申请记录。

<figure><img src="../../.gitbook/assets/image (196).png" alt=""><figcaption></figcaption></figure>

**2. 筛选条件**

* 国家：支持根据提现订单商户归属国家查询。
* 运营商：支持根据提现订单归属商户查询。
* 渠道：支持根据提现订单的渠道查询。
* 用户 ID：支持根据用户唯一ID查询。
* 订单状态：支持根据不同的提现状态查询（状态分类:待审核、待审查、审核拒绝、三方订单创建、提现失败、提现成功、审核拒绝并冻结）。
* 订单号：支持根据用户唯一订单号查询。
* 金额区间：支持根据提现金额范围查询。
* 首次提现：支持根据是否首次提现查询。
* 时间类型：支持根据提现申请时间或完成时间查询。
* 重置：清空所有筛选条件。
* 查询：根据筛选条件检索数据。

**3. 表格字段说明**

* ID：系统自动生成的提现订单编号。
* 运营商：提现用户来源商户。
* 渠道：提现用户来源渠道。
* 锁定：锁定后，其他人无法对该条进行操作，建议隐藏该字段。
* 用户ID：申请提现的用户唯一编号（可点击跳转到用户详情）。
* 危险等级：该用户的危险等级。
* 订单号：提现流水号。
* 提现真金金额：用户申请提现的真金金额。
* 提现彩金金额：用户申请提现的彩金金额。
* 提现手续费：提现产生的手续费。
* 提现信息：申请提现的用户信息。
* 首次提现：记录用户是否首次提现。
* 付款通道：提现订单调取的付款通道。
* 时间：提现订单的注册、申请、提交、完成时间。
* 提现方式：提现订单的付款方式。
* 订单状态：提现订单当前状态（待审核、审核通过、已打款、提现失败等）。
* 付款通道：提现订单调取的付款通道。
* 操作人员：订单操作人员账号。

·         操作->审核：点击后打开审核面板，可查看账号信息、注册信息、登录信息、历史存取款信息、本次取款信息、投注信息、优惠信息，并选择代付出款类型、审核结果并录入审核意见，如下图所示:

<figure><img src="../../.gitbook/assets/image (197).png" alt=""><figcaption></figcaption></figure>

运营人员审核通过后，用户收到提现成功邮件

<div align="left"><figure><img src="../../.gitbook/assets/image (198).png" alt="" width="232"><figcaption></figcaption></figure></div>

运营人员审核拒绝，对提现这笔金额设置打码倍数。

<div align="left"><figure><img src="../../.gitbook/assets/image (199).png" alt="" width="375"><figcaption></figcaption></figure></div>

审核拒绝后，用户收到提现拒绝邮件。

<div align="left"><figure><img src="../../.gitbook/assets/image (200).png" alt="" width="237"><figcaption></figcaption></figure></div>

运营人员审核拒绝并冻结，将冻结用户这笔提现金额。

<figure><img src="../../.gitbook/assets/image (201).png" alt=""><figcaption></figcaption></figure>

审核拒绝并冻结后，玩家收到提现冻结邮件，并在后台冻结解冻记录界面生成记录。

<div align="left"><figure><img src="../../.gitbook/assets/image (202).png" alt="" width="236"><figcaption></figcaption></figure></div>

用户通过三种方式解锁冻结金额:1.登录解锁 2.充值解锁  3.用户直属下级充值解锁

<div align="left"><figure><img src="../../.gitbook/assets/image (203).png" alt="" width="69"><figcaption></figcaption></figure></div>

<div align="left"><figure><img src="../../.gitbook/assets/image (204).png" alt="" width="129"><figcaption></figcaption></figure></div>

·         操作->提交审查：点击后打开提交审核确认面板，确认后，订单状态将进入待审查状态，需要风控人员重点审核后即可审核通过。

<figure><img src="../../.gitbook/assets/image (205).png" alt=""><figcaption></figcaption></figure>

4\. 批量操作与导出

* 批量勾选框：支持多选订单。
* 批量状态刷新：将选中的订单批量刷新状态。
* 批量审核：将选中的订单批量审核。
* 导出：导出筛选范围内的订单数据（Excel/CSV）。
