# 3-Step Plan: Testing Claude Code Functionality

## Step 1: Implement the Feature
Create a simple calculator module (`calculator.py`) with four operations:
- `add(a, b)` — addition
- `subtract(a, b)` — subtraction
- `multiply(a, b)` — multiplication
- `divide(a, b)` — division with zero-guard

## Step 2: Write Tests
Create `test_calculator.py` covering:
- Happy-path assertions for all four operations
- Edge cases (zero operands, negative numbers)
- Error handling (divide by zero raises `ValueError`)

## Step 3: Run & Verify
Install the test dependency and execute the test suite:
```bash
python3 -m pip install -r requirements-dev.txt
python3 -m pytest test_calculator.py -v
```
Expected output: 5 tests collected, 5 passed.
