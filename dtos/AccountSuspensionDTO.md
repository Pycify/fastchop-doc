# AccountSuspensionDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `suspensionType` | [SuspensionType](../enums/SuspensionType.md) | Enum: `user_account`, `rider_account`, `vendor_account`, `manager_account`, `vendor_business` |
| `userId` | string \| null | - |
| `businessId` | string \| undefined | - |
| `status` | [SuspensionStatus](../enums/SuspensionStatus.md) | Enum: `active`, `suspended` |
| `suspensionReason` | string \| null | - |
| `reactivationReason` | string \| null | - |
| `suspendedAt` | DateTime \| null | - |
| `reactivatedAt` | DateTime \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `user` | [UserDTO](../dtos/UserDTO.md) | - |
| `suspendedBy` | ActionDoneBy | - |
| `reactivatedBy` | ActionDoneBy | - |
