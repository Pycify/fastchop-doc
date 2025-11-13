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
| `id` | data.referrer.id, | - |
| `name` | data.referrer.fullName, | - |
| `email` | data.referrer.email, | - |
| `id` | data.referred.id, | - |
| `name` | data.referred.fullName, | - |
| `email` | data.referred.email, | - |
