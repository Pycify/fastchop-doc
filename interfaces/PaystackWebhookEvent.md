# PaystackWebhookEvent

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `event` | string | - |
| `data` | { | - |
| `id` | number | - |
| `status` | 'success' \| 'failed' \| 'pending' | - |
| `reference` | string | - |
| `amount` | number | - |
| `currency` | string | - |
| `paidAt` | string | - |
| `createdAt` | string | - |
| `channel` | string | - |
| `fees` | number \| null | - |
| `metadata` | [PaymentMetaData](../interfaces/PaymentMetaData.md) | - |
| `authorization` | { | - |
| `authorization_code` | string | - |
| `last4` | string | - |
| `exp_month` | string | - |
| `exp_year` | string | - |
| `card_type` | string | - |
| `bank` | string | - |
| `brand` | string | - |
| `reusable` | boolean | - |
| `signature` | string | - |
| `customer` | { | - |
| `id` | number | - |
| `email` | string | - |
| `customer_code` | string | - |
| `phone` | string \| null | - |
