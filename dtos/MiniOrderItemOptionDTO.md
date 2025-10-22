# MiniOrderItemOptionDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `itemName` | string | - |
| `quantity` | number | - |
| `mealOptionDisplay` | [MealOptionDisplay](../interfaces/MealOptionDisplay.md)[] | - |
| `unitPrice` | number | - |
| `currency` | string | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `name` | e.mealOption.groupName, | - |
| `optionItem` | data.orderItem.options.map((optionItem) => ({ | - |
| `name` | optionItem.mealOptionItem.name, | - |
| `quantity` | optionItem.quantity, | - |
| `display` | `${optionItem.quantity} x ${optionItem.mealOptionItem.name}`, | - |
