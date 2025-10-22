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
| `description` | string \| null | - |
| `referenceId` | string | - |
| `status` | [WalletTransactionStatus](../enums/WalletTransactionStatus.md) | Enum: `pending`, `completed`, `cancelled`, `failed` |
| `metadata` | Record<string, any> | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
