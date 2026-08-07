# [Cloudflare 推出可编程钱包](https://github.com/myogg/moon/issues/11)

在 AI 时代，智能体（Agent）想要尝试新的 API 或付费内容并不容易。它们既没有稳定的身份去注册，也无法像人类一样直接绑定信用卡，这大大限制了“智能体商业”的发展。

为了解决这一痛点，Cloudflare 宣布推出 Cloudflare Wallets，为 AI 智能体提供原生的支付与身份验证方案。

核心设计与功能：

•   双层钱包架构：
    •   账户钱包 (Account Wallets)：由人类账号所有者管理，负责资金充值与规则制定。
    •   虚拟钱包 (Virtual Wallets)：分配给 AI 智能体使用。人类可以为其设置“零花钱”限额、白名单和单次交易上限，让 AI 在可控风险内自主测试不同的 API 服务。
•   微支付支持：结合 Monetization Gateway，钱包利用 x402 协议实现了将支付信息直接附加在 HTTP 请求中，极大地简化了机器对机器的交易流程。
•   可读的智能体身份：用户可以为自己的账户申领 cloudflare.pay 域名。AI 智能体在访问服务时，可以通过如 research.example.cloudflare.pay 这样的可读标识公开身份，便于商家提供试用额度或进行白名单管理。

Cloudflare Wallets 的推出，意味着未来互联网将迎来一个专为 AI 设计的、无缝的“机器原生”交易市场。



