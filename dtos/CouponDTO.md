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
| `totalPayout` | number | - |
| `currency` | string | - |
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
