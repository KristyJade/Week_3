choice = "Y"

# Loop continues while the user wants to enter another student's marks
while choice.upper() == "Y":

    # Get quiz marks from the user
    quiz_1 = float(input("Enter Quiz 1 mark: "))
    quiz_2 = float(input("Enter Quiz 2 mark: "))
    quiz_3 = float(input("Enter Quiz 3 mark: "))

    # Calculate the average mark
    average = (quiz_1 + quiz_2 + quiz_3) / 3

    # Display the average mark
    print("Average Mark =", average)

    # Determine pass or fail
    if average >= 50:
        print("Pass")
    else:
        print("Fail")

    # Ask the user whether to continue
    choice = input("Continue? Select Y/N: ")

print("Program Ended")
