# MiniRiderRequestDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `orderNumber` | string | - |
| `vendorName` | string | - |
| `status` | [RiderRequestStatus](../enums/RiderRequestStatus.md) | Enum: `pending`, `accepted`, `rejected`, `expired`, `cancelled` |
| `estimatedEarnings` | number | - |
| `deliveryFee` | number | - |
| `pickupLocation` | [LocationDTO](../dtos/LocationDTO.md) | - |
| `deliveryLocation` | [LocationDTO](../dtos/LocationDTO.md) | - |
| `distanceFromVendorKm` | number | - |
| `expiresAt` | DateTime | - |
| `createdAt` | DateTime | - |
