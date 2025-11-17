# ReferralDTO

Referral DTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `status` | [ReferralStatus](../enums/ReferralStatus.md) | Enum: `pending`, `completed`, `expired` |
| `referralCode` | string | - |
| `rewardAmount` | number | - |
| `currency` | string | - |
| `orderId` | string \| null | - |
| `signupAt` | DateTime | - |
| `rewardedAt` | DateTime \| null | - |
| `notes` | string \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `referrer` | ActionDoneBy | - |
| `referred` | ActionDoneBy | - |
| `order` | [OrderMiniDTO](../dtos/OrderMiniDTO.md) \| null | - |
