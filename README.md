# Get user input as an integer
number = int(input("Enter a number: "))

# Classify the number into categories
if number < 0:
    print("The number is negative.")
elif number == 0:
    print("The number is zero.")
else:
    print("The number is positive.")
