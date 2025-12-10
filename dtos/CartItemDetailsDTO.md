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
| `currency` | string | - |
| `totalPrice` | number | - |
| `mealImage` | [MediaDTO](../dtos/MediaDTO.md) | - |
| `mealPack` | [MiniMealPackDTO](../dtos/MiniMealPackDTO.md) \| null | - |
| `mealPackDisplay` | [ItemDisplay](../interfaces/ItemDisplay.md) \| null | - |
| `mealOptionDisplay` | [MealOptionDisplay](../interfaces/MealOptionDisplay.md)[] | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `name` | data.pack.name, | - |
| `id` | data.pack.id, | - |
| `quantity` | data.quantity, | - |
| `display` | `${data.quantity} x ${data.pack.name}`, | - |
| `unitPrice` | data.pack.price, | - |
| `price` | data.pack.price * data.quantity, | - |
| `currency` | data.currency, | - |
| `name` | optionGroup[0].mealOption.groupName, | - |
| `id` | optionGroup[0].mealOption.id, | - |
| `optionItem` | optionGroup.map((optionItem) => ({ | - |
| `name` | optionItem.mealOptionItem.name, | - |
| `id` | optionItem.mealOptionItem.id, | - |
| `quantity` | optionItem.quantity, | - |
| `display` | `${optionItem.quantity} x ${optionItem.mealOptionItem.name}`, | - |
| `unitPrice` | optionItem.unitPrice, | - |
| `price` | optionItem.unitPrice * optionItem.quantity, | - |
| `currency` | optionItem.currency, | - |
