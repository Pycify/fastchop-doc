# AccountSuspensionDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `suspensionType` | [SuspensionType](../enums/SuspensionType.md) | Enum: `user_account`, `rider_account`, `vendor_account`, `vendor_business` |
| `userId` | string \| null | - |
| `businessId` | string \| null | - |
| `status` | [SuspensionStatus](../enums/SuspensionStatus.md) | Enum: `active`, `suspended` |
| `suspensionReason` | string \| null | - |
| `reactivationReason` | string \| null | - |
| `suspendedBy` | string \| null | - |
| `reactivatedBy` | string \| null | - |
| `suspendedAt` | DateTime \| null | - |
| `reactivatedAt` | DateTime \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `user` | [UserDTO](../dtos/UserDTO.md) | - |
| `suspendedByUser` | [UserDTO](../dtos/UserDTO.md) | - |
| `reactivatedByUser` | [UserDTO](../dtos/UserDTO.md) | - |
