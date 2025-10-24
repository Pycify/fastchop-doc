## 24th October 2023

**ADMIN BULK COMMUNICATIONS**

- POST /api/admin/bulk-communications
- GET /api/admin/bulk-communications
- GET /api/admin/bulk-communications/:id
- GET /api/admin/bulk-communications/:id/recipients
- POST /api/admin/bulk-communications/:id/retry-failed

**ADMIN USER MANAGEMENT**

- GET /api/admin/user-management/user
- GET /api/admin/user-management/user/:id
- GET /api/admin/user-management/order/:id
- GET /api/admin/user-management/transaction/:id

**REFERRAL**

- GET /api/referrals/:id
- GET /api/referrals/stats
- GET /api/referrals
- GET /api/referrals/admin/all
- GET /api/referrals/:code/stats
- GET /api/referrals/:code/referred-users

---

## 23rd October 2023

**WALLET**

- GET /api/wallet/bank-account
- POST /api/wallet/bank-account
- PATCH /api/wallet/bank-account

**COUPON**

- POST /api/coupons/validate
- GET /api/coupons/my-usage
- POST /api/coupons
- GET /api/coupons
- GET /api/coupons/:id
- PUT /api/coupons/:id
- POST /api/coupons/:id/cancel

**REFERRAL**

- GET /api/referrals/stats
- GET /api/referrals

---

### Order Checkout Payload

Now includes:

1. `couponCode: string?`
2. `useReferralBonus: boolean?`

### User Login Response

Now includes:

1. `bonusBalance: string`

> Refer to [OrderDTO](dtos/OrderDTO.md) and [UserDetailDTO](dtos/UserDetailDTO.md) for detailed response schema.
