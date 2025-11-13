# WalletTransactionDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `walletId` | string | - |
| `userId` | string | - |
| `transactionType` | [WalletTransactionType](../enums/WalletTransactionType.md) | Enum: `debit`, `credit` |
| `currency` | string | - |
| `amount` | number | - |
| `amountBefore` | number | - |
| `amountAfter` | number | - |
| `paymentMethod` | [PaymentMethod](../enums/PaymentMethod.md) \| null | - |
| `user` | ActionDoneBy | - |
| `description` | string \| null | - |
| `referenceId` | string | - |
| `status` | [WalletTransactionStatus](../enums/WalletTransactionStatus.md) | Enum: `pending`, `completed`, `cancelled`, `failed` |
| `metadata` | [PaymentMetaData](../interfaces/PaymentMetaData.md) | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
