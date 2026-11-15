# Python-2
# 1. عملگر جمع (+)
def addition(a, b):
    return a + b

# 2. عملگر تفریق (-)
def subtraction(a, b):
    return a - b

# 3. عملگر ضرب (*)
def multiplication(a, b):
    return a * b

# 4. عملگر تقسیم (/)
def division(a, b):
    return a / b

# 5. عملگر باقی مانده تقسیم (%)
def modulus(a, b):
    return a % b

# 6. عملگر توان (**)
def power(a, b):
    return a ** b

# 7. عملگر تقسیم صحیح (//)
def floor_division(a, b):
    return a // b

# 8. عملگر مساوی (==)
def equal(a, b):
    return a == b

# 9. عملگر نامساوی (!=)
def not_equal(a, b):
    return a != b

# 10. عملگر بزرگتر (>)
def greater_than(a, b):
    return a > b

# 11. عملگر کوچکتر (<)
def less_than(a, b):
    return a < b

# 12. عملگر بزرگتر یا مساوی (>=)
def greater_equal(a, b):
    return a >= b

# 13. عملگر کوچکتر یا مساوی (<=)
def less_equal(a, b):
    return a <= b

# 14. عملگر منطقی AND
def logical_and(a, b):
    return a and b

# 15. عملگر منطقی OR
def logical_or(a, b):
    return a or b

# 16. عملگر منطقی NOT
def logical_not(a):
    return not a


# نمایش نتایج توابع
print(addition(10, 5))
print(subtraction(10, 5))
print(multiplication(10, 5))
print(division(10, 5))
print(modulus(10, 3))
print(power(2, 3))
print(floor_division(10, 3))

print(equal(10, 10))
print(not_equal(10, 5))
print(greater_than(10, 5))
print(less_than(5, 10))
print(greater_equal(10, 10))
print(less_equal(5, 10))

print(logical_and(True, False))
print(logical_or(True, False))
print(logical_not(True))
