# Data Model (High Level)

## Core Entities
- User
- Store
- Product
- Order
- Payment
- Payout

## Multi-Tenant Design
- Every product & order linked to storeId
- Strict isolation between stores
- Platform maintains global visibility only
