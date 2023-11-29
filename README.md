# Unit2.Techspec
## prompt: a function called "mulitplication" that returns the product of the two input numbers.
# expectations: the function should accurately multiply the two input numbers and return the result.
# Positive Test 
## Standard Inputs:
# Input: multiplication(5, 3)
# Expected Output: 15
# Description: Test the function with standard positive integers to ensure correct multiplication.
# Positive Test 
## Decimal Inputs:
# Input: multiplication(2.5, 4.8)
# Expected Output: 12.0
# Description: Verify that the function correctly handles decimal inputs and produces accurate results.
# Positive Test
## Negative Input:
# Input: multiplication(-3, 7)
# Expected Output: -21
# Description: Ensure the function correctly handles cases where one input is negative.  

## Prompt: A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.
## Expectations: the function shoulder correctly sort odd numbers from both arrays
# the even elementd should be excluded from the result.
# the result array should be sorted in ascending order
# the function should handle edge cases
## Positive Test
# Standard Input:
# Test the function with standard inputs to ensure correct concatenation and sorting of odd numbers.
# Input: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1])
# Expected Output: [ -1, 1, 3, 9, 15 ]
## Negative Test 
# Checkif the function excludes even numbers from the result
# Input: concatOdds([2,4,6],[8,10,11,12])
# Expected Output:[11]
## Edge Test
## Large Numbers:
# Test the function with a large number to ensure it can handle large values
# Input: concatOdds([2345675, 12345678],[98765443, 46765432, 55960400])
# Expected Output: [2345675, 98765443]

## Prompt: A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.
# Funtional test for shopping cart checkout feature
## Positive Test
# Guest Checkout:
# Add items in cart
# Select guest checkout
# provide user information, ex. payment method
# complete the checkout process
# expected result: The user can successfully purchase an order without having to create an account
## Positive Test
# Account Owner Checkout
# Add items in carrt
# Log in as an exisitng user 
# Confirm the items in your cart
# Provide user information
# Complete checking out
# Expected result; the user successfully checks out as a logged in user, the order is associated with the users account
## Negitive test
# Empty cart:
# Open checkout with an empty cart
# attempt to checkout
# Expected result: system displays a prompt telling the user their cart is empty and cannot checkout
