# UserDetailDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `fullName` | string | - |
| `email` | string | - |
| `phone` | string \| null | - |
| `registerSource` | [RegisterSource](../enums/RegisterSource.md) | Enum: `standard`, `google`, `apple` |
| `userType` | [UserType](../enums/UserType.md) | Enum: `user`, `vendor`, `manager`, `deliverer`, `admin` |
| `referralCode` | string \| undefined | - |
| `emailVerifiedAt` | DateTime \| null | - |
| `accountStatus` | [SuspensionStatus](../enums/SuspensionStatus.md) | Enum: `active`, `suspended` |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime \| null | - |
| `userBalance` | string | - |
| `bonusBalance` | string | - |
| `hasWalletPin` | boolean | - |
| `suspensionInfo` | [AccountSuspensionDTO](../dtos/AccountSuspensionDTO.md) \| null | - |
| `verificationInfo` | [UserAccountVerification](../interfaces/UserAccountVerification.md) \| undefined | - |
| `storeStep` | [VendorSetupStep](../enums/VendorSetupStep.md) \| null \| undefined | - |
| `businessId` | string \| null \| undefined | - |
| `default` | return new UserDetailDTO(user) | - |
