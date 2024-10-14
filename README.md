def check_age(age):
    if age < 13:
        return "Leave"
    elif 13 <= age < 19:
        return "Grow up to 19"
    elif 19 <= age <= 50:
        return "Drink away"
    elif 51 <= age <= 70:
        return "Health warning"
    else:
        return "Life warning"

# Test cases
test_ages = [10, 15, 20, 55, 75]
for age in test_ages:
    print(f"Age {age}: {check_age(age)}")
