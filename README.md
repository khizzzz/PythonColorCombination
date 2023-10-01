# PythonColorCombination
Python Code to make a Color Combination :

PrimaryColour1= input("Enter the first Primary Colour =")
PrimaryColour2= input("Enter the second Primary Colour =")

if (PrimaryColour1 == "red" and PrimaryColour2 == "blue") or \
     (PrimaryColour1 == "blue" and PrimaryColour2 == "red") :
     print(PrimaryColour1 , "Mixed with", PrimaryColour2 ,"= Purple" )
elif (PrimaryColour1 == "blue" and PrimaryColour2 == "yellow") or \
     (PrimaryColour1 == "yellow" and PrimaryColour2 == "blue") :
     print(PrimaryColour1, "Mixed with", PrimaryColour2, "= Green")
elif (PrimaryColour1 == "red" and PrimaryColour2 == "yellow") or \
     (PrimaryColour1 == "yellow" and PrimaryColour2 == "red"):
     print(PrimaryColour1, "Mixed with", PrimaryColour2, "= Orange")
elif (PrimaryColour1 == "red" and PrimaryColour2 == "green") or \
     (PrimaryColour1 == "green" and PrimaryColour2 == "red"):
     print(PrimaryColour1, "Mixed with", PrimaryColour2, "= brown")

else :
     print("One of your provided colour is not Primary",PrimaryColour1, "or",PrimaryColour2, end=":")

