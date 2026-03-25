def calculate_area(length, width):
    return length * width

# Using the function
l = float(input("Enter length: "))
w = float(input("Enter width: "))

area = calculate_area(l, w)
print(f"The total area is: {area}")
