# RiderVerificationDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `rider` | [UserDTO](../dtos/UserDTO.md) | - |
| `verificationType` | [RiderVerificationType](../enums/RiderVerificationType.md) | Enum: `license`, `nin` |
| `licenseFrontDocument` | [MediaDTO](../dtos/MediaDTO.md) \| null | - |
| `licenseBackDocument` | [MediaDTO](../dtos/MediaDTO.md) \| null | - |
| `ninSlip` | [MediaDTO](../dtos/MediaDTO.md) \| null | - |
| `faceImage` | [MediaDTO](../dtos/MediaDTO.md) | - |
| `verificationState` | [VerificationStateType](../enums/VerificationStateType.md) | Enum: `verified`, `unverified`, `rejected`, `on_hold`, `pending` |
| `rejectionReason` | string \| null | - |
| `verifiedAt` | DateTime \| null | - |
| `rejectedAt` | DateTime \| null | - |
| `verifiedBy` | string \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
