# CouponDTO

Coupon Data Transfer Object

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `code` | string | - |
| `name` | string | - |
| `description` | string \| null | - |
| `bonusType` | [CouponBonusType](../enums/CouponBonusType.md) | Enum: `percentage`, `fixed` |
| `reward` | number | - |
| `maximumRedemptions` | number | - |
| `currentRedemptions` | number | - |
| `unit` | [CouponUnit](../enums/CouponUnit.md) | Enum: `NGN`, `%` |
| `startDate` | DateTime | - |
| `endDate` | DateTime | - |
| `status` | [CouponStatus](../enums/CouponStatus.md) | Enum: `active`, `expired`, `cancelled` |
| `createdBy` | ActionDoneBy | - |
| `cancelledBy` | ActionDoneBy \| null | - |
| `cancelledAt` | DateTime \| null | - |
| `cancellationReason` | string \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `id` | data.creator.id, | - |
| `name` | data.creator.fullName, | - |
| `email` | data.creator.email, | - |
| `id` | data.canceller.id, | - |
| `name` | data.canceller.fullName, | - |
| `email` | data.canceller.email, | - |
