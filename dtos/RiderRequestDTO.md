# RiderRequestDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `orderId` | string | - |
| `orderNumber` | string | - |
| `vendorName` | string | - |
| `status` | [RiderRequestStatus](../enums/RiderRequestStatus.md) | Enum: `pending`, `accepted`, `rejected`, `expired`, `cancelled` |
| `pickupLocation` | [LocationDTO](../dtos/LocationDTO.md) | - |
| `deliveryLocation` | [LocationDTO](../dtos/LocationDTO.md) | - |
| `distanceFromVendorKm` | number | - |
| `distanceFromCustomerKm` | number | - |
| `estimatedEarnings` | number | - |
| `deliveryFee` | number | - |
| `expiresAt` | DateTime | - |
| `respondedAt` | DateTime \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
