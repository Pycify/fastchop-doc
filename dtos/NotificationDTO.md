# NotificationDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `title` | string | - |
| `description` | string | - |
| `type` | [NotificationType](../enums/NotificationType.md) | Enum: `order_placed`, `order_accepted`, `order_preparing`, `order_ready`, `order_awaiting_rider`, `order_accepted_by_rider`, `order_picked_up`, `order_in_transit`, `order_delivered`, `order_cancelled`, `rider_request`, `meal_flagged`, `new_meal_added`, `business_verified`, `business_suspended`, `business_reactivated`, `new_review`, `manager_invited`, `manager_access_granted`, `manager_access_revoked`, `wallet_credited`, `wallet_debited`, `withdrawal_processed`, `withdrawal_failed`, `account_verified`, `account_suspended`, `password_changed`, `promo_announcement`, `system_update`, `bulk_message` |
| `readAt` | DateTime \| null | - |
| `actionData` | [NotificationActionDataDTO](../dtos/NotificationActionDataDTO.md) \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
