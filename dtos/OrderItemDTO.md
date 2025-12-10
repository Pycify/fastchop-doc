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
| `mealPackDisplay` | [ItemDisplay](../interfaces/ItemDisplay.md) \| null | - |
| `mealOptionDisplay` | [MealOptionDisplay](../interfaces/MealOptionDisplay.md)[] | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `name` | data.mealPack.name, | - |
| `id` | data.mealPack.id, | - |
| `quantity` | data.quantity, | - |
| `display` | `${data.quantity} x ${data.mealPack.name}`, | - |
| `unitPrice` | data.mealPack.price, | - |
| `price` | data.mealPack.price * data.quantity, | - |
| `currency` | data.currency, | - |
| `name` | option.mealOptionItem.name, | - |
| `id` | option.mealOptionItem.id, | - |
| `quantity` | option.quantity, | - |
| `display` | `${option.quantity} x ${option.mealOptionItem.name}`, | - |
| `unitPrice` | option.unitPrice, | - |
| `price` | option.unitPrice * option.quantity, | - |
| `currency` | option.currency, | - |
| `name` | option.mealOption.groupName, | - |
| `id` | option.mealOption.id, | - |
| `optionItem` | [item], | - |
