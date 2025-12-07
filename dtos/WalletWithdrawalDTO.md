# WalletWithdrawalDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `accountNumber` | string | - |
| `accountName` | string | - |
| `transactionId` | string | - |
| `withdrawalId` | string | - |
| `transferCode` | string | - |
| `amount` | number | - |
| `currency` | string | - |
| `status` | [WalletWithdrawalStatus](../enums/WalletWithdrawalStatus.md) | Enum: `pending`, `processing`, `completed`, `failed`, `reversed` |
| `transaction` | WalletTransaction | - |
| `withdrawal` | Withdrawal | - |
| `transfer` | [PaystackInitiateTransfer](../interfaces/PaystackInitiateTransfer.md) | - |
