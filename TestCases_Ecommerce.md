# Test Cases — Ecommerce Website

## 1. User Registration
| ID | Title | Steps | Expected Result |
|----|--------|--------|----------------|
| TC_REG_01 | Successful registration | 1. Open site<br>2. Go to Register<br>3. Enter valid data<br>4. Submit | Account is created and user is logged in |
| TC_REG_02 | Registration with existing email | Enter email already used | Error message displayed |

## 2. Login
| ID | Title | Steps | Expected Result |
|----|--------|--------|----------------|
| TC_LOG_01 | Login with valid credentials | Enter correct email/password | User is logged in |
| TC_LOG_02 | Invalid password | Enter wrong data | "Invalid credentials" displayed |

## 3. Product Search
| ID | Title | Steps | Expected Result |
|----|--------|--------|----------------|
| TC_SRCH_01 | Search valid product | Search "Laptop" | Results show laptops |
| TC_SRCH_02 | Empty search | Click search without input | Error tooltip or empty results page |

## 4. Add to Cart
| ID | Title | Steps | Expected Result |
|----|--------|--------|----------------|
| TC_CART_01 | Add product | Open product → Add to cart | Product appears in cart |
| TC_CART_02 | Remove product | Remove item | Cart becomes empty |

## 5. Checkout
| ID | Title | Steps | Expected Result |
|----|--------|--------|----------------|
| TC_CHK_01 | Checkout with valid data | Fill address + payment | Order is placed |
| TC_CHK_02 | Empty fields | Submit empty form | Validation errors appear |
