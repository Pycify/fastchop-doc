# NotificationDTO

## Properties

| Property | Type | Description |
|----------|------|-------------|
| `id` | string | - |
| `title` | string | - |
| `description` | string | - |
| `type` | [NotificationType](../enums/NotificationType.md) | Enum: `order_placed`, `order_accepted`, `order_preparing`, `order_unavailable_extras`, `order_user_confirmed`, `order_ready`, `order_awaiting_rider`, `order_accepted_by_rider`, `order_picked_up`, `order_in_transit`, `order_delivered`, `order_cancelled`, `order_auto_completed`, `rider_request`, `meal_flagged`, `meal_unflagged`, `new_meal_added`, `business_verified`, `business_rejected`, `new_review`, `manager_invited`, `manager_access_granted`, `manager_access_revoked`, `wallet_credited`, `wallet_debited`, `withdrawal_pending`, `withdrawal_processed`, `withdrawal_failed`, `withdrawal_reversed`, `rider_verified`, `rider_rejected`, `referral_used`, `referral_reward`, `store_opening`, `store_closing`, `account_verified`, `account_reactivated`, `account_suspended`, `password_changed`, `promo_announcement`, `system_update`, `bulk_message` |
| `imageUrl` | string \| null | - |
| `readAt` | DateTime \| null | - |
| `actionData` | [NotificationActionDataDTO](../dtos/NotificationActionDataDTO.md) \| null | - |
| `createdAt` | DateTime | - |
| `updatedAt` | DateTime | - |
