# OrderCancellationDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `orderId` | string | - |
| `cancelledBy` | ActionDoneBy | - |
| `reason` | string | - |
| `cancelledByRole` | [CancellationInitiator](../enums/CancellationInitiator.md) | Enum: `admin`, `vendor`, `customer` |
| `refundStatus` | [RefundStatus](../enums/RefundStatus.md) \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
