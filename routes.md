# API Routes Documentation

> Auto-generated from start/routes

### POST /api/admin/login
- Returns: —

### POST /api/admin/verify-otp
- Returns: —

### POST /api/admin/forgot-password
- Returns: —

### POST /api/admin/request-otp
- Returns: —

### POST /api/admin/reset-password
- Returns: —

### POST /api/admin/logout
- Returns: —

### GET /api/admin/bulk-communications/:id
- Returns: —

### GET /api/admin/bulk-communications/:id/recipients
- Returns: —

### POST /api/admin/bulk-communications/:id/retry-failed
- Returns: —

### GET /api/admin/dashboard/analytics
- Returns: —

### GET /api/admin/dashboard/user-growth-trends
- Returns: —

### GET /api/admin/dashboard/order-performance
- Returns: —

### GET /api/admin/dashboard/referral-payout
- Returns: —

### GET /api/admin/dashboard/revenue
- Returns: —

### GET /api/admin/dashboard/top-buyers
- Returns: —

### GET /api/admin/dashboard/top-vendors
- Returns: —

### GET /api/admin/dashboard/top-riders
- Returns: —

### GET /api/admin/user-management/:id
- Returns: —

### GET /api/admin/user-management/:id
- Returns: —

### GET /api/admin/user-management/:id
- Returns: —

### GET /api/analytics/top-selling-meals
- Returns: —

### POST /api/biometric/challenge
- Returns: —

### POST /api/biometric/verify
- Returns: —

### GET /api/business/:id/details
- Returns: [FullVendorDetailsDTO](./dtos/FullVendorDetailsDTO.md)

### GET /api/business/:id/reviews/detailed-rating
- Returns: —

### GET /api/business/:id/reviews
- Returns: —

### GET /api/business/list-all
- Returns: —

### GET /api/cart/index
- Returns: —

### GET /api/cart/:id
- Returns: —

### PUT /api/cart/:id/item-dupliate
- Returns: —

### DELETE /api/cart/:id/item-delete
- Returns: —

### DELETE /api/cart/:id/kitchen-delete
- Returns: —

### PATCH /api/cart/:id/note
- Returns: —

### POST /api/coupons/validate
- Returns: ⚠️ CouponValidationDTO
          isValid: validation.isValid,
          couponId: validation.coupon?.id,
          discountAmount: validation.discountAmount,
          finalAmount: validation.finalAmount,
          message: validation.message,
        }) (not documented)

### GET /api/coupons/my-usage
- Returns: [CouponUsageDTO](./dtos/CouponUsageDTO.md)

### GET /api/coupons/:id
- Returns: [CouponDTO](./dtos/CouponDTO.md)

### PUT /api/coupons/:id
- Returns: [CouponDTO](./dtos/CouponDTO.md)

### POST /api/coupons/:id/cancel
- Returns: [CouponDTO](./dtos/CouponDTO.md)

### POST /api/favourites/toggle
- Returns: —

### GET /api/favourites/businesses
- Returns: —

### GET /api/favourites/meals
- Returns: —

### POST /api/meal/create
- Returns: [MealDTO](./dtos/MealDTO.md)

### POST /api/meal/meal-type
- Returns: [MealTypeDTO](./dtos/MealTypeDTO.md)

### PATCH /api/meal/meal-type/:id
- Returns: [MealTypeDTO](./dtos/MealTypeDTO.md)

### DELETE /api/meal/meal-type/:id
- Returns: —

### POST /api/meal/option-item
- Returns: [MealOptionItemDTO](./dtos/MealOptionItemDTO.md)

### PATCH /api/meal/option-item/:id
- Returns: [MealOptionItemDTO](./dtos/MealOptionItemDTO.md)

### DELETE /api/meal/option-item/:id
- Returns: —

### POST /api/meal/meal-pack
- Returns: [MealPackDTO](./dtos/MealPackDTO.md)

### PATCH /api/meal/meal-pack/:id
- Returns: [MealPackDTO](./dtos/MealPackDTO.md)

### DELETE /api/meal/meal-pack/:id
- Returns: —

### POST /api/meal/meal-option
- Returns: [MealOptionDTO](./dtos/MealOptionDTO.md)

### PATCH /api/meal/meal-option/:id
- Returns: [MealOptionDTO](./dtos/MealOptionDTO.md)

### DELETE /api/meal/meal-option/:id
- Returns: —

### POST /api/meal/meal
- Returns: [MealDTO](./dtos/MealDTO.md)

### GET /api/meal/meal/:id
- Returns: [MealDTO](./dtos/MealDTO.md)

### PATCH /api/meal/meal/:id
- Returns: [MealDTO](./dtos/MealDTO.md)

### DELETE /api/meal/meal/:id
- Returns: —

### GET /api/meal/meal-type
- Returns: —

### GET /api/meal/meal-type/:id
- Returns: [MealTypeDTO](./dtos/MealTypeDTO.md)

### GET /api/meal/option-item
- Returns: —

### GET /api/meal/option-item/:id
- Returns: [MealOptionItemDTO](./dtos/MealOptionItemDTO.md)

### GET /api/meal/meal-pack
- Returns: —

### GET /api/meal/meal-pack/:id
- Returns: [MealPackDTO](./dtos/MealPackDTO.md)

### GET /api/meal/meal-option
- Returns: —

### GET /api/meal/meal-option/:id
- Returns: [MealOptionDTO](./dtos/MealOptionDTO.md)

### GET /api/meal/meal
- Returns: —

### GET /api/meal/meal-category
- Returns: [MealCategoryDTO](./dtos/MealCategoryDTO.md)

### POST /api/misc/autocomplete
- Returns: —

### GET /api/misc/place-details/:placeId
- Returns: —

### POST /api/misc/reverse-geocode
- Returns: —

### POST /api/misc/static-map
- Returns: —

### POST /api/misc/calculate-delivery-fee
- Returns: —

### GET /api/misc/faq
- Returns: —

### GET /api/misc/support
- Returns: —

### POST /api/misc/send-email
- Returns: —

### GET /api/order/index
- Returns: —

### GET /api/order/:id
- Returns: [OrderDTO](./dtos/OrderDTO.md)

### GET /api/referrals/:id
- Returns: [ReferralDTO](./dtos/ReferralDTO.md)

### GET /api/referrals//stats
- Returns: ⚠️ ReferralStatsDTO
          referralCode: user.referralCode,
          user: user,
          ...stats,
        }) (not documented)

### POST /api/reports/report-business
- Returns: —

### GET /api/reports/report-reasons
- Returns: [ReportReasonDTO](./dtos/ReportReasonDTO.md)

### GET /api/rider/requests
- Returns: —

### GET /api/rider/requests/:id
- Returns: —

### POST /api/rider/requests/:id/accept
- Returns: —

### POST /api/rider/requests/:id/reject
- Returns: —

### POST /api/rider/verify
- Returns: [RiderVerificationDTO](./dtos/RiderVerificationDTO.md)

### GET /api/share/store/:id
- Returns: —

### GET /api/transaction/list-banks
- Returns: —

### POST /api/transaction/verify-account
- Returns: —

### POST /api/transaction/webhook
- Returns: —

### POST /api/transaction/initialize-payment
- Returns: —

### GET /api/transaction/list
- Returns: —

### GET /api/transaction/:id
- Returns: —

### POST /api/user/login-other-source
- Returns: —

### POST /api/user/logout
- Returns: —

### DELETE /api/user/delete
- Returns: —

### PATCH /api/user/edit
- Returns: [UserDTO](./dtos/UserDTO.md)

### POST /api/wallet/create-pin
- Returns: —

### POST /api/wallet/bank-account
- Returns: [BankAccountDTO](./dtos/BankAccountDTO.md)

### GET /api/wallet/bank-account
- Returns: [BankAccountDTO](./dtos/BankAccountDTO.md)

### PATCH /api/wallet/bank-account
- Returns: [BankAccountDTO](./dtos/BankAccountDTO.md)

