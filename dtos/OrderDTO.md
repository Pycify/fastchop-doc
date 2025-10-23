# OrderDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `orderDisplayName` | string | - |
| `orderNumber` | string | - |
| `status` | string | - |
| `deliveryType` | string | - |
| `customer` | [UserDTO](../dtos/UserDTO.md) | - |
| `paymentMethod` | string | - |
| `paymentStatus` | string | - |
| `subtotal` | number | - |
| `deliveryFee` | number | - |
| `totalAmount` | number | - |
| `discountAmount` | number | - |
| `currency` | string | - |
| `preparationTime` | string \| null | - |
| `specialInstructions` | string \| null | - |
| `business` | [VendorBusinessDTO](../dtos/VendorBusinessDTO.md) | - |
| `deliveryLocation` | [LocationDTO](../dtos/LocationDTO.md) \| null | - |
| `coupon` | [CouponDTO](../dtos/CouponDTO.md) \| null | - |
| `items` | [OrderItemDTO](../dtos/OrderItemDTO.md)[] | - |
| `orderCancellation` | [OrderCancellationDTO](../dtos/OrderCancellationDTO.md) \| null | - |
| `orderCompletion` | [OrderCompletionDTO](../dtos/OrderCompletionDTO.md) \| null | - |
| `orderAcceptance` | [OrderAcceptanceDTO](../dtos/OrderAcceptanceDTO.md) \| null | - |
| `orderStarted` | [OrderStartedPreparationDTO](../dtos/OrderStartedPreparationDTO.md) \| null | - |
| `orderReadyForPickup` | [OrderReadyForPickupDTO](../dtos/OrderReadyForPickupDTO.md) \| null | - |
| `awaitingRider` | [OrderAwaitingRiderDTO](../dtos/OrderAwaitingRiderDTO.md) \| null | - |
| `pickedUpByRider` | [OrderPickedUpByRiderDTO](../dtos/OrderPickedUpByRiderDTO.md) \| null | - |
| `inTransit` | [OrderInTransitDTO](../dtos/OrderInTransitDTO.md) \| null | - |
| `orderTimeline` | Partial<Record<OrderStatus, DateTime \| null>> | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
