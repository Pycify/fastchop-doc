# UserDetailDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `fullName` | string | - |
| `email` | string | - |
| `phone` | string \| null | - |
| `registerSource` | [RegisterSource](../enums/RegisterSource.md) | Enum: `standard`, `google`, `apple` |
| `userType` | [UserType](../enums/UserType.md) | Enum: `user`, `vendor`, `deliverer`, `admin` |
| `referralCode` | string \| undefined | - |
| `emailVerifiedAt` | DateTime \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime \| null | - |
| `userBalance` | string | - |
| `bonusBalance` | string | - |
| `hasWalletPin` | boolean | - |
| `verificationInfo` | [UserAccountVerification](../interfaces/UserAccountVerification.md) \| undefined | - |
| `storeStep` | [VendorSetupStep](../enums/VendorSetupStep.md) \| null \| undefined | - |
| `businessId` | string \| null \| undefined | - |
| `default` | return new UserDetailDTO(user) | - |
