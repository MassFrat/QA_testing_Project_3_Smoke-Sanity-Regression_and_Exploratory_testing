# Test Plan — Project 3
## nopCommerce Demo Store | Structured Manual Testing

---

| Field | Details |
|---|---|
| **Project** | Project 3 — nopCommerce Structured Testing |
| **Tester** | Mass Frat |
| **Date** | May 2026 |
| **Version** | 1.0 |
| **Application** | nopCommerce Demo Store |
| **URL** | https://demo.nopcommerce.com |
| **Browser** | Firefox (latest version) |
| **Screen Resolution** | Desktop — 1920 x 1080 |

---

## 1. Objectives

- Verify that all major features of the nopCommerce demo store work correctly
- Practise and demonstrate four key manual testing types: Smoke, Sanity, Regression and Exploratory
- Identify, document and report defects with clear reproduction steps and severity ratings
- Produce a professional, portfolio-ready test project for GitHub and job applications

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
| **Regression** | Full re-test — did the change break anything? | 20 | After any significant code change |
| **Exploratory** | Unscripted creative investigation | 1 session (45 min) | After regression is complete |
| **Total** | | **38** | |

---

## 4. Test Environment

| Component | Detail |
|---|---|
| **Browser** | Firefox (latest) |
| **Developer Tools** | Firefox Developer Tools — F12 (Console, Network, Responsive Design Mode) |
| **Operating System** | Windows / macOS |
| **Screen Size** | 1920 x 1080 (desktop) |
| **Mobile Testing** | Firefox Responsive Design Mode — iPhone 14 Pro (390px) |
| **Test Documentation** | Google Sheets |
| **Screen Recording** | Loom (exploratory session) |
| **Bug Tracking** | Google Sheets — Bugs tab |
| **Portfolio** | GitHub |

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
- All 20 regression test cases have been executed and results recorded
- All bugs found are logged with severity, reproduction steps and screenshots
- The 45-minute exploratory session is complete and recorded on Loom
- A final test summary report has been completed

---

## 6. Test Deliverables

| Deliverable | Format | Location |
|---|---|---|
| Test Plan | `.md` | `test-plan.md` |
| Smoke Test Cases + Results | `.xlsx` | `smoke-tests.xlsx` |
| Sanity Test Cases + Results | `.xlsx` | `sanity-tests.xlsx` |
| Regression Test Suite + Results | `.xlsx` | `regression-tests.xlsx` |
| Exploratory Session Notes | `.md` | `exploratory-session-notes.md` |
| Bug Report | `.md` | `bug-report.md` |
| Test Summary Report | `.xlsx` | `test-summary-report.xlsx` |
| Screenshots | `.png` | `screenshots/` folder |

---

## 7. Risks & Mitigations

| Risk | Likelihood | Mitigation |
|---|:---:|---|
| Demo site unavailable | Low | Switch to OpenCart demo (demo.opencart.com) as backup |
| Demo data resets between sessions | Medium | Re-create test data at the start of each session |
| Test data shared with other demo users | Medium | Prefix all test data with **MF_** (e.g. MF_TestUser) |
| Loom recording fails | Low | Test recording before starting. Use Firefox screenshot tool as backup |

---

## 8. Estimated Schedule

| Activity | Estimated Time |
|---|---|
| Explore application + write test plan | 30 minutes |
| Smoke testing (10 test cases) | 30 minutes |
| Sanity testing (8 test cases) | 30 minutes |
| Regression testing (20 test cases) | 2 – 3 hours |
| Exploratory testing session | 45 minutes |
| Bug logging + bug report | 30 minutes |
| GitHub upload + README | 30 minutes |
| **Total Estimated Time** | **~5 – 6 hours** |

---

## 9. Bug Severity Guide

| Severity | Definition |
|:---:|---|
| 🔴 Critical | Core feature completely broken — application is unusable |
| 🟠 High | Major feature broken — needs urgent fix before release |
| 🟡 Medium | Feature impacted but a workaround exists |
| 🟢 Low | Minor cosmetic or usability issue with no functional impact |

---

## 10. Sign-off

| Role | Name | Date | Signature |
|---|---|---|---|
| Tester | Mass Frat | May 2026 | ✅ |
| Reviewer | | | |
| Test Manager | | | |

---

*Test Plan v1.0 — Project 3 — nopCommerce Structured Testing — Mass Frat — May 2026*
