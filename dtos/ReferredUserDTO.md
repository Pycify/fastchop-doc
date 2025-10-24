# ReferredUserDTO

Referred User DTO (for list)

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `name` | string | - |
| `email` | string | - |
| `phone` | string | - |
| `status` | [ReferralStatus](../enums/ReferralStatus.md) | Enum: `pending`, `completed`, `expired` |
| `signupAt` | DateTime | - |
| `rewardedAt` | DateTime \| null | - |
| `rewardedAmount` | number \| null | - |
| `currency` | string \| null | - |
| `hasCompletedOrder` | boolean | - |
| `orderNumber` | string \| null | - |
