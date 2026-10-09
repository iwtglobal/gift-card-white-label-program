# White-Label Program Setup Checklist

Launch checklist for a **branded gift card program** on a shared gift card / electronic voucher platform.

## 1. Commercial and legal pack

- [ ] Program agreement: who is issuer, who is processor
- [ ] Customer T&Cs: expiry, fees, lost/stolen, refunds
- [ ] Brand licence for artwork and name use
- [ ] Settlement calendar and chargeback / fraud allocation
- [ ] Data processing roles (controller / processor) documented

## 2. Product catalogue

| Item | Confirm |
|------|---------|
| SKUs / denominations | List and currencies |
| Reloadable vs fixed value | Explicit per SKU |
| Activation model | Instant vs delayed (corporate) |
| Redemption scope | Single brand / mall list / wider |
| Partial redeem | Supported yes/no |

## 3. Brand kit

- [ ] Card face and digital image assets (print + screen sizes)
- [ ] SMS / email / receipt copy in required languages
- [ ] Support phone / URL printed on card
- [ ] Packaging rules for physical cards (if any)

## 4. Channels and inventory

- [ ] Issuance channels enabled (POS, web, bulk API, EVD agents)
- [ ] Single inventory pool or channel-split pools — decide and document
- [ ] PIN / card number format and check-digit rules
- [ ] Low-stock alerts per SKU

## 5. Go-live controls

- [ ] Test cards in a non-prod tenant redeemed end-to-end
- [ ] Ops users under least privilege for the brand tenant
- [ ] Daily outstanding liability report signed off by finance
- [ ] Fraud rule baselines (velocity, geo, bulk redeem)
- [ ] Runbook: stop-sell, freeze SKU, mass deactivate batch

## Related

See the main [README](../README.md). Product context: [voucher management system](https://evdsystem.com/voucher-management-system-mobogage/).
