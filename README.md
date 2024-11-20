
# Mohammed Anas
# Date: 11-19-2024
# Module 9: Lab Activity – While Loops

# Problem 1: Infinite Loop
# Uncomment the code below to test the infinite loop.
# To break the loop, use Ctrl-C or Command-C.

# while True:
#    print("Infinite")

# Problem 2: Counter-Controlled While Loop
L = [57, 83]  # Initializing the list
counter = 0  # Initializing the counter
while counter <= 10:
    L.append(counter)
    counter += 1
print(f"The list has {len(L)} elements.")
print(f"The third element in the list is {L[2]}.")

# Problem 3: Sum-Controlled While Loop
numbers = []  # List to store entered numbers
total = 0  # Sum of the numbers
while total <= 100:
    num = int(input("Enter a number: "))
    numbers.append(num)
    total += num
print(f"The numbers entered are: {numbers}")
print(f"The total sum is: {total}")
