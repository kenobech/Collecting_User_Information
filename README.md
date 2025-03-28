# Collecting User Information

This project is a Python-based script designed to collect and validate user information interactively. It provides a user-friendly interface for entering personal details, validates the input, and allows users to restart or enter information for multiple individuals.

## Features

- **Input Validation**: Ensures that user inputs are valid, with support for default values and type casting.
- **Customizable Options**: Allows specifying valid options for fields like gender and education level.
- **Interactive Flow**: Users can restart the process or enter information for multiple individuals.
- **Exit Option**: Users can type `exit` at any prompt to terminate the program.

## Collected Information

The script collects the following details:
1. Full Name (default: "Anonymous")
2. Age (integer)
3. Gender (options: Male, Female, Other)
4. Country of Birth (default: "Unknown")
5. Highest Level of Education (options: High School, Bachelor's, Master's, PhD)
6. Certifications (default: "None")
7. Job Applying For (default: "Not Specified")
8. Salary Expectation (float)

## How to Use

1. Run the script in a Python environment.
2. Follow the prompts to enter the required information.
3. Type `exit` at any prompt to terminate the program.
4. After entering all details, review the summary of the collected information.
5. Choose to restart the process or enter information for another individual.

## Example Usage

```plaintext
Enter your Full Name (or type 'exit' to quit): John Doe
Enter your Age (or type 'exit' to quit): 30
Enter your Gender (Male, Female, Other) (or type 'exit' to quit): Male
Enter your Country of Birth (or type 'exit' to quit): USA
Enter your highest level of education (High School, Bachelor's, Master's, PhD) (or type 'exit' to quit): Bachelor's
Enter your certifications (or type 'exit' to quit): None
Enter the job you are applying for (or type 'exit' to quit): Software Engineer
Enter your Salary Expectation (or type 'exit' to quit): 75000

User Information Summary:
==============================
Full Name: John Doe
Age: 30
Gender: Male
Country of Birth: USA
Highest Level of Education: Bachelor's
Certification: None
Job Applying For: Software Engineer
Salary Expectation: 75000.0
==============================
```

## Notes

- Ensure Python is installed on your system to run the script.
- The script is designed to handle invalid inputs gracefully and provide helpful error messages.

## License

This project is open-source and available for use under the MIT License.
