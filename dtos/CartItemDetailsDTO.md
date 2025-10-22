# CartItemDetailsDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `mealName` | string | - |
| `mealPreparationTime` | string \| null | - |
| `quantity` | number | - |
| `note` | string \| null | - |
| `totalPrice` | number | - |
| `mealPack` | [MiniMealPackDTO](../dtos/MiniMealPackDTO.md) | - |
| `mealPackDisplay` | [MealItemDisplay](../interfaces/MealItemDisplay.md) | - |
| `mealOptionDisplay` | [MealOptionDisplay](../interfaces/MealOptionDisplay.md)[] | - |
| `currency` | string | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `name` | data.pack.name, | - |
| `quantity` | data.quantity, | - |
| `display` | `${data.quantity} x ${data.pack.name}`, | - |
| `name` | e.mealOption.groupName, | - |
| `optionItem` | data.options.map((optionItem) => ({ | - |
| `name` | optionItem.mealOptionItem.name, | - |
| `quantity` | optionItem.quantity, | - |
| `display` | `${optionItem.quantity} x ${optionItem.mealOptionItem.name}`, | - |
