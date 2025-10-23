# 23rd October 2023

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
- GET /api/referrals/admin

Order Checkout Payload now includes

1. couponCode: string?
2. useReferralBonus: boolean?

User Login Response now includes

1. bonusBalance: string

Refer to [OrderDTO](https://github.com/Pycify/fastchop-doc/blob/master/dtos/OrderDTO.md), [UserDetailDTO](https://github.com/Pycify/fastchop-doc/blob/master/dtos/UserDetailDTO.md) for details
