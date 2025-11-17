# ManagerDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `user` | ActionDoneBy | - |
| `vendor` | ActionDoneBy | - |
| `status` | [ManagerStatus](../enums/ManagerStatus.md) | Enum: `pending`, `active` |
| `invitedAt` | DateTime | - |
| `acceptedAt` | DateTime \| null | - |
| `businesses` | [VendorSmallBusinessDTO](../dtos/VendorSmallBusinessDTO.md)[] | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
