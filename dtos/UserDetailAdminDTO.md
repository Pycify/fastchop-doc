# UserDetailAdminDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `fullName` | string | - |
| `email` | string | - |
| `phone` | string \| null | - |
| `registerSource` | [RegisterSource](../enums/RegisterSource.md) | Enum: `standard`, `google`, `apple` |
| `userType` | [UserType](../enums/UserType.md) | Enum: `user`, `vendor`, `deliverer`, `admin` |
| `referralCode` | string | - |
| `referralSignup` | string \| null | - |
| `referralCount` | number | - |
| `emailVerifiedAt` | DateTime \| null | - |
| `totalOrders` | number | - |
| `verificationInfo` | [UserAccountVerification](../interfaces/UserAccountVerification.md) \| undefined | - |
| `branches` | number \| undefined | - |
| `business` | [VendorBusinessDTO](../dtos/VendorBusinessDTO.md) \| undefined | - |
| `totalDeliveries` | number \| undefined | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime \| null | - |
