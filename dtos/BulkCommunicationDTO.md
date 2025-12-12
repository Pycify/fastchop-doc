# BulkCommunicationDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `createdBy` | string | - |
| `title` | string | - |
| `content` | string | - |
| `channels` | [CommunicationChannel](../enums/CommunicationChannel.md)[] | Enum: `email`, `sms`, `push_notification` |
| `targetType` | [CommunicationUserTargetType](../enums/CommunicationUserTargetType.md) | Enum: `all_users`, `users`, `vendors`, `deliverers`, `verified_users`, `unverified_users`, `custom` |
| `totalRecipients` | number | - |
| `sentCount` | number | - |
| `failedCount` | number | - |
| `deliveredCount` | number | - |
| `status` | [CommunicationStatus](../enums/CommunicationStatus.md) | Enum: `pending`, `processing`, `completed`, `failed`, `partially_completed` |
| `image` | [MediaDTO](../dtos/MediaDTO.md) \| null | - |
| `successRate` | number | - |
| `scheduledAt` | DateTime \| null | - |
| `startedAt` | DateTime \| null | - |
| `completedAt` | DateTime \| null | - |
| `errorMessage` | string \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
| `creator` | [UserDTO](../dtos/UserDTO.md) | - |
