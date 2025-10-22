# OrderCancellationDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `orderId` | string | - |
| `cancelledBy` | [ActionDoneBy](../interfaces/ActionDoneBy.md) | - |
| `reason` | string | - |
| `cancelledByRole` | [CancelledByRole](../enums/CancelledByRole.md) | Enum: `customer`, `vendor`, `admin` |
| `refundStatus` | [RefundStatus](../enums/RefundStatus.md) \| null | - |
| `id` | data.cancelledByUser.id, | - |
| `name` | data.cancelledByUser.fullName, | - |
| `email` | data.cancelledByUser.email, | - |
