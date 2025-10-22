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
| `emailVerifiedAt` | DateTime \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime \| null | - |
| `userBalance` | string | - |
| `hasWalletPin` | boolean | - |
| `verificationInfo` | [UserAccountVerification](../interfaces/UserAccountVerification.md) \| undefined | - |
| `storeStep` | [VendorSetupStep](../enums/VendorSetupStep.md) \| null | - |
| `businessId` | string \| null | - |
| `default` | return new UserDetailDTO(user) | - |
