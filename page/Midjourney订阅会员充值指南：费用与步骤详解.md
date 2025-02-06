# Midjourney订阅会员充值指南：费用与步骤详解

## 如何订阅Midjourney？

在Midjourney服务器或通过Midjourney Bot聊天窗口，输入`/subscribe`并按下回车：

![Subscription Command](https://bbtdd.com/img/86649043620.webp)

Bot会发送一条包含“Open subscription”按钮的消息，点击后即可进入付费页面：

![Subscription Page](https://bbtdd.com/img/85026908.webp)

Midjourney的付费功能由Stripe提供服务，目前仅支持信用卡支付。确保您拥有一张有效的信用卡以完成订阅。

## Midjourney订阅套餐详解

以下为截至2023年3月28日的Midjourney订阅套餐详情：

| 套餐类型       | 月付价格   | 年付价格   | Fast Generations | Concurrent Fast Jobs | Relaxed Generations | Stealth Mode |
|----------------|------------|------------|------------------|----------------------|---------------------|--------------|
| Basic Plan     | $10/month  | $8/month   | 3小时 (约200张图) | 3                    | ❌                  | ❌           |
| Standard Plan  | $30/month  | $24/month  | 15小时           | 3                    | ✅                  | ❌           |
| Pro Plan       | $60/month  | $48/month  | 30小时           | 12                   | ✅                  | ✅           |

### 计费方式与影响因素

Midjourney采用时间计费方式，与OpenAI的Token计费不同。主要成本在于GPU计算，因此计费基于GPU使用时间。以下因素会影响费用：

- **图片质量与个性化**：质量越高，个性化因素越多，费用越高。
- **任务类型**：如Variations、Upscale等操作会消耗更多资源。
- **长宽比**：非默认长宽比会额外收费。
- **模型版本**：某些模型版本（如`--test`或`--testp`）费用更高。
- **图像质量参数**：如`--q 2`比默认`--q 1`更贵。
- **停止参数**：如`--stop 10`到`--stop 99`会调整费用。

### Relaxed Generation模式

Standard Plan及以上套餐用户可使用Relaxed Generation模式，该模式下用户可无限出图，但生成速度会变慢（通常0-10分钟）。此模式本质上是利用GPU空闲资源进行排队。

**注意事项**：

1. **等待时间**：使用Relaxed模式越多，等待时间越长。
2. **月度重置**：每月初系统会自动切换回Fast模式。

### Stealth模式

Pro版本用户可启用Stealth模式，以防止生成的图片被公开至Midjourney Gallery。但请注意，在Discord公开频道生成的图片仍会被公开。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)