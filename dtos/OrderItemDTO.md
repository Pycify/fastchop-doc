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
| `mealOptionDisplay` | [MealOptionDisplay](../interfaces/MealOptionDisplay.md)[] | - |
| `options` | [MiniOrderItemOptionDTO](../dtos/MiniOrderItemOptionDTO.md)[] | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `name` | data.mealPack.name, | - |
| `quantity` | data.quantity, | - |
| `display` | `${data.quantity} x ${data.mealPack.name}`, | - |
| `price` | data.mealPack.price * data.quantity, | - |
| `currency` | data.currency, | - |
| `name` | option.mealOptionItem.name, | - |
| `quantity` | option.quantity, | - |
| `display` | `${option.quantity} x ${option.mealOptionItem.name}`, | - |
| `price` | option.unitPrice * option.quantity, | - |
| `currency` | option.currency, | - |
| `name` | option.mealOption.groupName, | - |
| `optionItem` | [item], | - |
