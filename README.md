# GoTo Group (Gojek + Tokopedia) (goto-gojek)

GoTo Group (PT GoTo Gojek Tokopedia Tbk) is Indonesia's largest
digital ecosystem, formed by the 2021 merger of ride-hailing /
on-demand superapp Gojek and e-commerce marketplace Tokopedia. It
operates three business pillars: On-Demand Services (Gojek — ride
hailing GoRide / GoCar, food delivery GoFood, parcel delivery
GoSend, logistics GoBox, courier GoSend), E-Commerce (Tokopedia
marketplace and Mitra Tokopedia), and Financial Technology (GoTo
Financial — GoPay, GoPayLater, GoInvestasi). In 2024 GoTo divested
Tokopedia's e-commerce operations to TikTok Shop / ByteDance,
retaining a 25% stake in the combined Tokopedia–TikTok Shop
entity; the developer.tokopedia.com portal now redirects to
TikTok Shop's partner platform. GoTo continues to operate Gojek
and GoTo Financial directly. There is no single GoTo group-wide
developer portal — partner integrations happen at the product
level (Gojek partner programs, GoPay PSP integrations, TikTok
Shop Open Platform for the former Tokopedia surface).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/goto-gojek/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/goto-gojek/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Partner

## Tags

- Superapp
- Ride Hailing
- Food Delivery
- Last-Mile Logistics
- E-commerce
- Digital Payments
- Indonesia
- Southeast Asia
- Gojek
- Tokopedia

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### GoSend Logistics API

GoSend is Gojek's on-demand last-mile courier service. The
GoSend API lets e-commerce platforms, marketplaces, and ERP
systems book GoSend Instant and Same-Day deliveries, fetch
quotes, track couriers, and receive lifecycle webhook events
for Indonesia coverage.

- **Human URL:** [https://www.gojek.com/en-id/gosend/](https://www.gojek.com/en-id/gosend/)
- **Base URL:** `https://api.gojekapi.com`

#### Tags

- Last-Mile
- Couriers
- Indonesia
- Logistics

#### Properties

- [Product Page](https://www.gojek.com/en-id/gosend/)
- [Business Integration](https://www.gojek.com/en-id/gosend/integrate/)
- [Postman Collection](collections/goto-gojek.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/goto-gojek.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GoBiz Merchant Platform

GoBiz is the merchant operating platform for restaurants and
retailers selling through GoFood and Gojek's on-demand
services. Partner POS / SaaS vendors integrate with GoBiz to
manage menus, store availability, order acknowledgement, and
fulfillment.

- **Human URL:** [https://gobiz.co.id/](https://gobiz.co.id/)
- **Base URL:** `https://api.gobiz.co.id`

#### Tags

- Merchant
- POS
- GoFood
- Menus
- Orders

#### Properties

- [Product Page](https://gobiz.co.id/)
- [Postman Collection](collections/goto-gojek.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/goto-gojek.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GoPay Payments API

GoPay is GoTo Financial's e-money and digital wallet platform
in Indonesia. Online and offline merchants integrate via
partner payment service providers (e.g. Midtrans, Xendit,
DOKU) to accept GoPay for wallet checkout, QRIS, and
recurring billing.

- **Human URL:** [https://gopay.co.id/](https://gopay.co.id/)
- **Base URL:** `https://api.gopay.co.id`

#### Tags

- Payments
- Digital Wallet
- QRIS
- Indonesia

#### Properties

- [Product Page](https://gopay.co.id/)
- [Merchant Info](https://gopay.co.id/merchant)
- [Postman Collection](collections/goto-gojek.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/goto-gojek.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Midtrans Payment Gateway API

Midtrans is GoTo Financial's payment service provider business
in Indonesia. The Midtrans API offers full payment gateway
coverage — credit/debit cards, bank transfer (Permata,
Mandiri, BCA, BNI), e-wallets (GoPay, ShopeePay, OVO, DANA),
installments, and QRIS — for Indonesian merchants.

- **Human URL:** [https://docs.midtrans.com/](https://docs.midtrans.com/)
- **Base URL:** `https://api.midtrans.com`

#### Tags

- Payments
- Payment Gateway
- Indonesia
- Cards
- E-Wallets
- QRIS

#### Properties

- [Documentation](https://docs.midtrans.com/)
- [API Reference](https://docs.midtrans.com/en/welcome/index.html)
- [Postman Collection](collections/goto-gojek.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/goto-gojek.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moka POS Platform

Moka is GoTo Financial's cloud POS for Indonesian SMBs,
acquired in 2020. It exposes integration APIs and webhooks
for inventory sync, sales reporting, employee management,
and customer loyalty programs.

- **Human URL:** [https://www.mokapos.com/](https://www.mokapos.com/)
- **Base URL:** `https://app.mokapos.com`

#### Tags

- POS
- SMB
- Indonesia
- Inventory

#### Properties

- [Product Page](https://www.mokapos.com/)
- [Postman Collection](collections/goto-gojek.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/goto-gojek.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tokopedia / TikTok Shop Open Platform

Following GoTo's 2024 divestment of Tokopedia's e-commerce
operations to TikTok Shop, integrations for what was formerly
the Tokopedia Open API and Mitra Tokopedia developer surface
are now served via the TikTok Shop Partner Center, which
covers products, orders, fulfillment, returns, finance, and
marketing across the combined Tokopedia + TikTok Shop
marketplace in Indonesia.

- **Human URL:** [https://partner.tiktokshop.com/docv2/page/overview](https://partner.tiktokshop.com/docv2/page/overview)
- **Base URL:** `https://open-api.tiktokglobalshop.com`

#### Tags

- E-commerce
- Marketplace
- Tokopedia
- TikTok Shop
- Orders
- Products

#### Properties

- [Documentation](https://partner.tiktokshop.com/docv2/page/overview)
- [Partner Center](https://partner.tiktokshop.com/)
- [Postman Collection](collections/goto-gojek.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/goto-gojek.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Corporate Website](https://www.gotocompany.com/)
- [Gojek Website](https://www.gojek.com/)
- [Tokopedia Website](https://www.tokopedia.com/)
- [Go To Financial](https://www.gotofinancial.com/)
- [Go Send](https://www.gojek.com/en-id/gosend/)
- [Go Biz](https://gobiz.co.id/)
- [Go Pay](https://gopay.co.id/)
- [Midtrans](https://midtrans.com/)
- [Midtrans Docs](https://docs.midtrans.com/)
- [Moka P O S](https://www.mokapos.com/)
- [Tik Tok Shop Partner](https://partner.tiktokshop.com/)
- [Investor Relations](https://www.gotocompany.com/investor-relations)
- [Newsroom](https://www.gotocompany.com/newsroom)
- [Sustainability](https://www.gotocompany.com/sustainability)
- [Careers](https://www.gotocompany.com/careers)
- [Git Hub Gojek](https://github.com/gojek)
- [Git Hub Tokopedia](https://github.com/tokopedia)
- [LinkedIn](https://www.linkedin.com/company/gotocompany/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
