# PaystackTransaction

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | number | - |
| `domain` | string | - |
| `status` | [PaystackTransactionStatus](../enums/PaystackTransactionStatus.md) | Enum: `pending`, `success`, `abandoned`, `failed` |
| `reference` | string | - |
| `receipt_number` | string \| null | - |
| `message` | string \| null | - |
| `gateway_response` | string | - |
| `paid_at` | string \| null | - |
| `created_at` | string | - |
| `currency` | string | - |
| `metadata` | OrderPaymentMetaData | - |
| `fees` | number \| null | - |
