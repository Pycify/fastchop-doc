# CardTransactionDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `reference` | string | - |
| `amount` | number | - |
| `currency` | string | - |
| `status` | [PaymentStatus](../enums/PaymentStatus.md) | Enum: `pending`, `completed`, `failed`, `refunded`, `reversed` |
| `paymentMethod` | [PaymentMethod](../enums/PaymentMethod.md) | Enum: `wallet`, `card` |
| `metadata` | [PaymentMetaData](../interfaces/PaymentMetaData.md) | - |
| `paidAt` | DateTime \| null | - |
| `createdAt` | DateTime | - |
