# 🧮 Discount Calculator – PLP July 2025

## Overview
This project contains a Python script that calculates the final price of an item after applying a discount. The discount is only applied if the percentage is **20% or higher**, in accordance with the challenge instructions.

## Files
- `discount_calculator.py`: Main script containing the `calculate_discount` function and user input logic.

## Function Description

```python
def calculate_discount(price, discount_percent):
    if discount_percent >= 20:
        return price - (price * discount_percent / 100)
    else:
        return price
