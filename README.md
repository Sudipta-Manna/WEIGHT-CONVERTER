# WEIGHT-CONVERTER
It convert weight into Kilogram and POUNDs
weight = float(input("Enter your weight: "))
unit = input("Kilograms or Pounds? (K or L): ").upper()

if unit == "K":
    weight = weight * 2.205
    unit_label = "Lbs"
    print(f"Your weight is: {round(weight, 1)} {unit_label}")

elif unit == "L":
    weight = weight / 2.205
    unit_label = "kgs"
    print(f"Your weight is: {round(weight, 1)} {unit_label}")

else:
    print(f"{unit} was not valid")
