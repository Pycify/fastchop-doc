# VendorBusinessDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `walletId` | string | - |
| `ownerId` | string | - |
| `name` | string | - |
| `businessCode` | string | - |
| `about` | string | - |
| `phone` | string \| null | - |
| `email` | string \| null | - |
| `isOpenStatus` | boolean | - |
| `isDefault` | boolean | - |
| `isCurrentSelected` | boolean | - |
| `setupStep` | [VendorSetupStep](../enums/VendorSetupStep.md) \| null | - |
| `fromAmount` | number | - |
| `currency` | string | - |
| `shareUrl` | string \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `verifiedAt` | DateTime \| null | - |
| `verificationState` | [VerificationStateType](../enums/VerificationStateType.md) | Enum: `verified`, `unverified`, `rejected`, `on_hold`, `pending` |
| `images` | MediaDTO[] \| null | - |
