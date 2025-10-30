# ManagerDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `user` | [ActionDoneBy](../interfaces/ActionDoneBy.md) | - |
| `vendor` | [ActionDoneBy](../interfaces/ActionDoneBy.md) | - |
| `status` | [ManagerStatus](../enums/ManagerStatus.md) | Enum: `pending`, `active` |
| `invitedAt` | DateTime | - |
| `acceptedAt` | DateTime \| null | - |
| `businesses` | [VendorSmallBusinessDTO](../dtos/VendorSmallBusinessDTO.md)[] | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `id` | manager.user.id, | - |
| `name` | manager.user.fullName, | - |
| `email` | manager.user.email, | - |
| `id` | manager.vendor.id, | - |
| `name` | manager.vendor.fullName, | - |
| `email` | manager.vendor.email, | - |
