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
| `storeStatus` | [SuspensionStatus](../enums/SuspensionStatus.md) | Enum: `active`, `suspended` |
| `setupStep` | [VendorSetupStep](../enums/VendorSetupStep.md) \| null | - |
| `fromAmount` | number | - |
| `currency` | string | - |
| `shareUrl` | string \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `verifiedAt` | DateTime \| null | - |
| `verificationState` | [VerificationStateType](../enums/VerificationStateType.md) | Enum: `verified`, `unverified`, `rejected`, `on_hold`, `pending` |
| `images` | MediaDTO[] \| null | - |
