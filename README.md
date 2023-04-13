# multiplication table generator
Request of user input for a number. This short code generates a times table up to 12


print(" MULTIPLICATION TABLE GENERATOR")
print("================================\n")

# Ask user for a number they want times table for

userNumber = int(input("Enter a number between 1 to 10 inclusive: "))

print('\n')

# Generate a multiplication table for user input
for i in range(1, 13):
 print(i, 'x', userNumber, '=', i * userNumber,'\n')
