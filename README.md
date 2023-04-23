# Adding New Feature to the Lending Software

This project is to add a new feature, which is prompting the user to save the qualifying loans as a new CSV file, to the existing lending software.

## Technologies

The following technologies are required to use this project:

- Python 3.7+
- Libraries: `sys`, `csv`, `questionary`, `fire`, `pathlib`
- Operating system: Windows, macOS, or Linux

## Installation Guide

1. Clone the repository from GitHub:

    ```
    git clone https://github.com/Demigodgeek/-C2_Add_Features_to_Loan_Qualifier_Application.git
    ```

2. Install the required Python libraries:

    ```
    pip install fire questionary
    ```

    Note: if you're not using a virtual environment, you may need to use `pip3` instead of `pip`.

## Usage

1. Open a terminal or command prompt and navigate to the directory where you cloned the repository.

2. Run the program with the following command:

    ```
    python app.py
    ```

3. Answer the prompts to input the required information.

4. When prompted, first enter a filepath `data/daily_rate_sheet.csv` to load the CSV file.

5. Input the credit score, the current amount of monthly debt, the tatal monthly income, the desired loan amount, and the home value.

6. Input Yes if you want to save the qualifying loans.

7. Enter the path you want to save the new csv file `data/qualifying_loans.csv`

5. The new CSV file will be saved in the data folder as the `qualifying_loans.csv` file.

## Contributors

- Demi Gao

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.