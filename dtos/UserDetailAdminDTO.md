# UserDetailAdminDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `fullName` | string | - |
| `email` | string | - |
| `phone` | string \| null | - |
| `registerSource` | [RegisterSource](../enums/RegisterSource.md) | Enum: `standard`, `google`, `apple` |
| `userType` | [UserType](../enums/UserType.md) | Enum: `user`, `vendor`, `manager`, `deliverer`, `admin` |
| `referralCode` | string | - |
| `referralSignup` | string \| null | - |
| `referralCount` | number | - |
| `emailVerifiedAt` | DateTime \| null | - |
| `totalOrders` | number | - |
| `accountStatus` | [SuspensionStatus](../enums/SuspensionStatus.md) | Enum: `active`, `suspended` |
| `verificationInfo` | [UserAccountVerification](../interfaces/UserAccountVerification.md) \| undefined | - |
| `suspensionInfo` | [AccountSuspensionDTO](../dtos/AccountSuspensionDTO.md) \| null | - |
| `businesses` | BranchWithDelivery[] \| undefined | - |
| `totalDeliveries` | number \| undefined | - |
| `riderVerificationStep` | [RiderVerificationStep](../enums/RiderVerificationStep.md) \| undefined \| null | - |
| `riderInformation` | RiderPersonalInfoDTO \| undefined \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime \| null | - |
