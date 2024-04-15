# Minimum_and_maximum_of_an_array
This Java application is designed to generate an array of random numbers, based on user input, and then analyze it to find the minimum and maximum values.


**Description:**

It provides a straightforward way for users to engage with random data and observe the range of variability within a specified number of random entries.

**Functionality:**

- **Input Collection:** The program prompts the user to specify the number of random numbers they wish to generate.
- **Random Number Generation:** Once a valid positive integer is provided, the program generates an array of that size with random numbers ranging from 1 to 500.
- **Output of Numbers:** The random numbers are then printed in rows, each containing up to 10 numbers, for easy viewing.
- **Analysis of Numbers:** After displaying the numbers, the program calculates and displays the smallest and largest numbers in the array.

**Usage:**

1. **Start the Program:** Run the application.
2. **Enter Number of Elements:** Input the number of random numbers you want the program to generate. This number must be a positive integer.
3. **View Results:** The numbers will be displayed in formatted rows followed by the minimum and maximum values found in the generated array.

**Error Handling:**

- The program includes error handling to ensure that only positive integers are accepted as input. If a non-integer or a non-positive integer is entered, the program will prompt the user to enter a valid number.

**Example:**

- **Prompt:** "From how many numbers he wanted to create an array: "
- **Input:** 30
- **Output:**
  - Random numbers displayed in formatted rows.
  - "Lower Number is: [smallest-number]"
  - "Highest Number is: [largest-number]"
