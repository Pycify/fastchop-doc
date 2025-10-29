# OrderItemDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `quantity` | number | - |
| `totalAmount` | number | - |
| `currency` | string | - |
| `note` | string \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `meal` | [MiniMealDTO](../dtos/MiniMealDTO.md) | - |
| `pack` | [MiniMealPackDTO](../dtos/MiniMealPackDTO.md) \| null | - |
| `mealPackDisplay` | [MealItemDisplay](../interfaces/MealItemDisplay.md) \| null | - |
| `options` | [MiniOrderItemOptionDTO](../dtos/MiniOrderItemOptionDTO.md)[] | - |
| `name` | data.mealPack.name, | - |
| `quantity` | data.quantity, | - |
| `display` | `${data.quantity} x ${data.mealPack.name}`, | - |
