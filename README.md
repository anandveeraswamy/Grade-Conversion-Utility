# Grade Conversion Utility – Problem Statement

You are required to implement a JavaScript module that converts student grades between three different grading systems used in higher education. The goal is to build a small, well-structured program that performs accurate conversions, validates inputs, and handles errors appropriately.

## Supported Grade Systems

### 1. Percentage Scale (0–100%)
This is the raw numeric score.  
A pass is **40% or above**.

### 2. Merit/Distinction System
- **Distinction:** 70–100%  
- **Merit:** 60–69%  
- **Pass:** 40–59%  
- **Fail:** 0–39%  

### 3. Degree Classification System
- **First Class:** 70–100%  
- **Upper Second (2:1):** 60–69%  
- **Lower Second (2:2):** 50–59%  
- **Third Class:** 40–49%  
- **Fail:** 0–39%  

## Your Task

You must:

- Implement a **main conversion function** that converts a grade from one system to another.
- Implement small, **pure helper functions** for individual conversions (e.g., percentage → merit).
- **Validate all inputs.**  
  - Invalid percentages  
  - Unrecognised grade labels  
  - Unsupported conversion types  
  These should all produce clear error messages.
- **Normalise input**, such as by converting grade labels to uppercase.
- Organise your solution using **ES modules**.

## Unit Testing Requirements

Write **unit tests using Jest** that verify:

- Correct conversions between all supported systems.
- All boundary conditions (e.g., 39%, 40%, 59%, 60%, 69%, 70%).
- Proper error handling for invalid inputs.

## Deliverable

The final program should be:

- Robust  
- Easy to read  
- Structured using good JavaScript practices  

This exercise is designed to help you practise modular code design, pure functions, data-driven logic, and unit testing with Jest.
