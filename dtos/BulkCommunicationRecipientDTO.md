# BulkCommunicationRecipientDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `userId` | string | - |
| `channel` | [CommunicationChannel](../enums/CommunicationChannel.md) | Enum: `email`, `sms`, `push_notification` |
| `status` | [CommunicationRecipientStatus](../enums/CommunicationRecipientStatus.md) | Enum: `pending`, `sent`, `failed`, `delivered`, `read` |
| `errorMessage` | string \| null | - |
| `sentAt` | DateTime \| null | - |
| `deliveredAt` | DateTime \| null | - |
| `readAt` | DateTime \| null | - |
| `user` | [UserDTO](../dtos/UserDTO.md) | - |
