# Automation Links

This file lists which Playwright specs cover specific requirements captured in
the Requirements Traceability Matrix (RTM).  It is provided as an adjunct to
the Excel file and is not intended to replace it.

| Requirement ID | Description | Automated Spec |
|----------------|-------------|---------------|
| R-LOGIN-01 | User can log in with valid credentials | `tests/auth/login.spec.ts` – @smoke login test |
| R-LOGIN-02 | User receives an error when entering invalid password | `tests/auth/login.spec.ts` – invalid password test |
| R-SEARCH-01 | User can search for products by keyword | `tests/catalog/search.spec.ts` – search for an existing product |
| R-SEARCH-02 | System displays a message when no products match the search | `tests/catalog/search.spec.ts` – no results test |
| R-CART-01 | User can add a product to the cart | `tests/cart-checkout/add-to-cart.spec.ts` |
| R-CHECKOUT-01 | User can complete a purchase | `tests/cart-checkout/checkout-happy-path.spec.ts` |
| R-PROFILE-01 | User can upload a profile avatar | `tests/profile/avatar-upload.spec.ts` |

Refer to the RTM spreadsheet (`rtm.xlsx`) for the full list of requirements and
their test coverage status.  Automated links are updated as new tests are
created.