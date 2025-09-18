# Myntra Automation Testing (Add to Cart Flow)

## Overview
This project automates the **Add to Cart** functionality on [Myntra](https://www.myntra.com/), 
demonstrating test case design, strategy, and execution using Selenium with Python.

## Tools & Framework
- **Automation Tool**: Selenium WebDriver
- **Language**: Python
- **Framework**: unittest
- **Browser**: Chrome

## Functionalities Tested
1. Search for a product (e.g., "Shoes")
2. Add product to cart
3. Validate product in cart

## Test Case Design
| **ID**  | **Scenario** | **Steps** | **Expected Result** |
|---------|--------------|-----------|----------------------|
| TC101   | Add product to cart | 1. Navigate to myntra.com <br> 2. Search for a product <br> 3. Click on first result <br> 4. Select size <br> 5. Click **Add to Bag** <br> 6. Open Bag | Product is successfully added to the cart |

## Test Strategy
- Focused on **critical user journey**: product search → add to cart.
- Covered both UI elements and functional validations.
- Assertions included for verifying product presence in the cart.

## Rationale
- Add to Cart is a **core e-commerce flow** impacting business KPIs.
- High priority since cart failures directly affect revenue.
- Chosen to demonstrate **end-to-end automation** of a key feature.

## Running the Tests
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/Myntra-Automation-Tests.git
   cd Myntra-Automation-Tests
