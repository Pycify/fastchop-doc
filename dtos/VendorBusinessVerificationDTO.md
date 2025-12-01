# VendorBusinessVerificationDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `businessId` | string | - |
| `identificationNumber` | string | - |
| `isBusinessRegistered` | boolean | - |
| `verificationState` | [VerificationStateType](../enums/VerificationStateType.md) | Enum: `verified`, `unverified`, `rejected`, `pending` |
| `rejectionReason` | string \| null | - |
| `verifiedAt` | DateTime \| null | - |
| `rejectedAt` | DateTime \| null | - |
| `verifiedBy` | ActionDoneBy \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `faceImage` | [MediaDTO](../dtos/MediaDTO.md) \| null | - |
| `verificationDoc` | [MediaDTO](../dtos/MediaDTO.md) \| null | - |
