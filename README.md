def print_months():
    # List of month names
    months = [
        "January", "February", "March", "April", "May", "June",
        "July", "August", "September", "October", "November", "December"
    ]

    # Print each month with its corresponding number
    for i, month in enumerate(months, start=1):
        print(f"Month {i}: {month}")

if __name__ == "__main__":
    print_months()
