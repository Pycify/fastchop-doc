# OrderCancellationDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `orderId` | string | - |
| `cancelledBy` | ActionDoneBy | - |
| `reason` | string | - |
| `cancelledByRole` | [CancelledByRole](../enums/CancelledByRole.md) | Enum: `customer`, `vendor`, `admin` |
| `refundStatus` | [RefundStatus](../enums/RefundStatus.md) \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `id` | data.cancelledByUser.id, | - |
| `name` | data.cancelledByUser.fullName, | - |
| `email` | data.cancelledByUser.email, | - |
