# CartItemDetailsDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `mealId` | string | - |
| `mealName` | string | - |
| `mealPreparationTime` | string \| null | - |
| `quantity` | number | - |
| `note` | string \| null | - |
| `totalPrice` | number | - |
| `mealImage` | [MediaDTO](../dtos/MediaDTO.md) | - |
| `mealPack` | [MiniMealPackDTO](../dtos/MiniMealPackDTO.md) \| null | - |
| `mealPackDisplay` | [MealItemDisplay](../interfaces/MealItemDisplay.md) \| null | - |
| `mealOptionDisplay` | [MealOptionDisplay](../interfaces/MealOptionDisplay.md)[] | - |
| `currency` | string | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `name` | data.pack.name, | - |
| `quantity` | data.quantity, | - |
| `display` | `${data.quantity} x ${data.pack.name}`, | - |
| `price` | data.pack.price * data.quantity, | - |
| `currency` | data.currency, | - |
| `name` | optionGroup[0].mealOption.groupName, | - |
| `optionItem` | optionGroup.map((optionItem) => ({ | - |
| `name` | optionItem.mealOptionItem.name, | - |
| `quantity` | optionItem.quantity, | - |
| `display` | `${optionItem.quantity} x ${optionItem.mealOptionItem.name}`, | - |
| `price` | optionItem.unitPrice * optionItem.quantity, | - |
| `currency` | optionItem.currency, | - |
