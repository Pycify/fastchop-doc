# FullVendorDetailsDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `walletId` | string | - |
| `ownerId` | string | - |
| `name` | string | - |
| `businessCode` | string | - |
| `about` | string | - |
| `phone` | string \| null | - |
| `email` | string \| null | - |
| `ownerInfo` | [UserDTO](../dtos/UserDTO.md) | - |
| `setupStep` | [VendorSetupStep](../enums/VendorSetupStep.md) \| null | - |
| `isOpenStatus` | boolean | - |
| `isDefault` | boolean | - |
| `isCurrentSelected` | boolean | - |
| `isFavourite` | boolean \| undefined | - |
| `verificationState` | string | - |
| `storeStatus` | [SuspensionStatus](../enums/SuspensionStatus.md) | Enum: `active`, `suspended` |
| `verificationInfo` | [UserAccountVerification](../interfaces/UserAccountVerification.md) | - |
| `fromAmount` | number | - |
| `currency` | string | - |
| `shareUrl` | string \| null | - |
| `ratings` | [VendorRating](../interfaces/VendorRating.md) | - |
| `verifiedAt` | DateTime \| null | - |
| `businessLocation` | [LocationDTO](../dtos/LocationDTO.md) \| null | - |
| `hours` | BusinessHourDTO[] \| null | - |
| `images` | MediaDTO[] \| null | - |
| `reviewsCount` | number | - |
| `storeManagers` | ActionDoneBy[] | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `rating` | data.reviews.length > 0 | - |
| `base` | 5, | - |
| `totalReviews` | data.reviews.length, | - |
