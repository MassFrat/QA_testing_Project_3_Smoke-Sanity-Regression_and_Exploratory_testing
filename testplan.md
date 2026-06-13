## Test Plan — Project 3
### nopCommerce Demo Store | Structured Manual Testing

---

| Field | Details |
|---|---|
| **Project** | Project 3 — nopCommerce Structured 4 Types of Testing |
| **Tester** | Mass Frat |
| **Date** | May/June 2026 |
| **Version** | 1.0 |
| **Application** | nopCommerce Demo Store |
| **URL** | https://demo.nopcommerce.com |
| **Browser** | Firefox/Chrome (latest versions) |
| **Screen Resolution** | Desktop — 1920 x 1080 |

---

## 1. Objectives

- Verify that all major features of the nopCommerce demo store work correctly
- Practice and demonstrate four key manual testing types: Smoke, Sanity, Regression and Exploratory
- Identify, document and report defects with clear reproduction steps and severity r

---

## 2. Scope

### ✅ In Scope

| Module | Features Covered |
|---|---|
| Homepage & Navigation | Page load, navigation menu, footer links, logo |
| Search & Filters | Search results, no-results handling, sort by price |
| Product Pages | Image gallery, option selectors, wish list |
| Shopping Cart | Add, update quantity, remove, subtotal calculation |
| Checkout | Address form, field validation, shipping, order placement, order history |
| User Account | Registration, login, edit profile, wrong password, forgot password |

### ❌ Out of Scope

- Admin panel and backend configuration
- Real payment processing or live card transactions
- Backend database or API-level testing
- Performance, load or security penetration testing

---

## 3. Test Approach

| Test Type | Purpose | Test Cases | When It Runs |
|---|---|:---:|---|
| **Smoke** | Quick check — is the app alive and stable? | 10 | First — before every session |
| **Sanity** | Verify a specific bug fix worked correctly | 8 | After a developer deploys a fix |
| **Regression** | Full re-test — did the change break anything? | 35 | 
| **Exploratory** | Unscripted creative investigation | 1 session (25 mins) | 
| **Total** | | **53** | |

---

## 4. Test Environment

| Component | Detail |
|---|---|
| **Browser** | Firefox/Chrome (latest) |
| **Developer Tools** | Firefox/Chrome Developer Tools — F12 (Console, Network, Responsive Design Mode) |
| **Operating System** | Windows |
| **Screen Size** | 1920 x 1080 (desktop) |
| **Mobile Testing** | Firefox/Chrome Responsive Design Mode — iPhone 14 Pro (390px) |
| **Test Documentation** | Google Sheets/MS Word |
| **Screen Recording** | Loom (exploratory session) |

---

## 5. Entry & Exit Criteria

### Entry Criteria — Testing begins when:

- The nopCommerce homepage loads without errors
- The main navigation menu is visible and functional
- A test account can be registered and logged in successfully
- At least one product can be found, added to cart and the checkout page reached

### Exit Criteria — Testing ends when:

- All 10 smoke test cases have been executed and results recorded
- All 8 sanity test cases have been executed and results recorded
- All 35 regression test cases have been executed and results recorded
- All bugs found are logged with severity, reproduction steps and screenshots
- The 25-minute exploratory session is complete and recorded on Loom

---

## 6. Bug Severity Guide

| Severity | Definition |
|:---:|---|
| 🔴 Critical | Core feature completely broken — application is unusable |
| 🟠 High | Major feature broken — needs urgent fix before release |
| 🟡 Medium | Feature impacted but a workaround exists |
| 🟢 Low | Minor cosmetic or usability issue with no functional impact |

---


