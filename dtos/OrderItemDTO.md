# OrderItemDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `quantity` | number | - |
| `totalAmount` | number | - |
| `currency` | string | - |
| `note` | string \| null | - |
| `meal` | [MiniMealDTO](../dtos/MiniMealDTO.md) | - |
| `pack` | [MiniMealPackDTO](../dtos/MiniMealPackDTO.md) \| null | - |
| `mealPackDisplay` | [MealItemDisplay](../interfaces/MealItemDisplay.md) \| null | - |
| `options` | [MiniOrderItemOptionDTO](../dtos/MiniOrderItemOptionDTO.md)[] | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `name` | data.mealPack.name, | - |
| `quantity` | data.quantity, | - |
| `display` | `${data.quantity} x ${data.mealPack.name}`, | - |
