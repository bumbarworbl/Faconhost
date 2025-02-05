# OpenAI API 收费标准及 Token 计算方式：中文汉字对应多少 Token？

OpenAI 的用户体系分为 ChatGPT 用户和开发者用户，两者虽然使用相同的用户名和密码，但登录入口和支付方式独立：

- **ChatGPT 用户**的登录入口：[https://chat.openai.com](https://bbtdd.com/WildCard)
- **API 开发者用户**的登录入口：[https://platform.openai.com](https://bbtdd.com/WildCard)

[![OpenAI 用户体系](https://bbtdd.com/img/165678652878.webp)](https://bbtdd.com/WildCard)

## OpenAI GPT Plus 会员与 API 使用权限

ChatGPT 用户可以通过购买 GPT Plus 会员（20 美元/月）获得 GPT-4 的使用权限，购买后可在 Chat 界面选择 GPT-4 进行对话。开发者用户则需绑定信用卡并预充值 5 美元以上，才能获取 GPT-4 API 的使用权限。

OpenAI 会根据充值金额设置消费限额，例如充值 5 美元，API 调用消费上限也为 5 美元。用户可设置自动充值功能，当余额低于指定值（如 5 美元）时，系统会自动从绑定卡中扣款充值。

[![自动充值设置](https://bbtdd.com/img/8761407117893265.webp)](https://bbtdd.com/WildCard)

如果连续两次扣费失败（如卡内余额不足），OpenAI 可能会封禁开发者账户及对应卡号。开发者用户可在[官方窗口](https://platform.openai.com/account/usage)实时查看 API 消费情况。

[![API 消费查看](https://bbtdd.com/img/4968346765878.webp)](https://bbtdd.com/WildCard)

## OpenAI API 收费标准

OpenAI ChatGPT API 按模型收费，不同版本（如 GPT-3.5、GPT-4）价格不同。以下是官方公布的 API 价格（具体以实际为准）：

### GPT-3.5 Turbo API 价格

### GPT-4 API 价格

| 模型          | 输入（Input）  | 输出（Output）  |
|---------------|----------------|-----------------|
| 8K context    | $0.03 / 1K tokens | $0.06 / 1K tokens |
| 32K context   | $0.06 / 1K tokens | $0.12 / 1K tokens |

GPT-4 API 价格约为 GPT-3.5 的 20 倍。

## OpenAI API Token 计算方式

在 OpenAI API 中，Token 是计价单位。以下是 Token 与语言单位的关系：

- **1K Token ≈ 750 个英文单词**
- **1K Token ≈ 500 个中文汉字**
- **1K Token ≈ 0.002 美元**

OpenAI 提供了在线工具 [Tokenizer](https://platform.openai.com/tokenizer)，帮助用户计算特定文本使用的 Token 数量。

[![Tokenizer 工具](https://bbtdd.com/img/984879599814.webp)](https://bbtdd.com/WildCard)

例如，英文单词“ChatGPT”占用 3 个 Token，“AI”占用 1 个 Token；中文汉字如“的”、“是”、“一”通常占用 1 个 Token，但大部分汉字占用 2 个 Token。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)