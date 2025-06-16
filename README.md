# Budget_allocation_app

## Overview
The Budget Allocation App is a command-line interface (CLI) tool designed to help users optimize their monthly income through tailored budgeting and expense planning. The app calculates how users can best allocate their income across various expense categories by distributing the remaining income after fixed expenses have been deducted. It provides a visual breakdown of spending in table format and a pie chart saved as a PNG file.

## Features
- Collects monthly income and fixed expenses from the user.
- Calculates budget allocation for categories such as Savings, Investments, Dining Out, and Guilt-Free Spending after fixed expenses.
- Displays formatted budget tables and a pie chart visualization.
- Supports multiple calculations.
- Includes error handling and input validation.

## System Requirements
- Python 3.8 or higher.
- Required Python libraries (install via pip):
  - `matplotlib`
  - `tabulate`
  - `colorama`
  - `pyfiglet`

Install dependencies by running:
```bash
pip install matplotlib tabulate colorama pyfiglet
```

## Installation Steps
Inside the terminal:

1. Create new folder for repository to be saved in and change your directory to be in the folder.
    ```
    mkdir Budget_allocation_app
    cd Budget_allocation_app
    ```
2. Clone this repository to your local machine via terminal.
   
    ```
    git clone git@github.com:Angie-newbie/Budget_allocation_app.git
    ```
    
3. To start open and code in your chosen IDE:
   ```
   code .
   ```
   
5. Create virtual environment to install dependencies in your IDE:
   
   Create virtual environment in your chosen IDE
   ```
   python3 -m venv .venv
   ```
   Activate the environment
   macOS/Unix
   ```
   source .venv/bin/activate
   ```
   Windows
   ```
   .venv\Scripts\activate
   ```
   Verify activation
   ```
   python --version
   ```
   Check installed packages & create output into requirements.txt file
   ```
   pip freeze > requirements.txt
   ```
6. Install the required dependencies:
    ```
    pip install matplotlib tabulate colorama pyfiglet
    ```

## Usage of app
To run the Budget Allocation App
In termimal:
```
python main.py
```
To terminate the Budget Allocation App, use ctrl + c keys together to exit the app. 

## Prompts
- Enter monthly income when prompted
- Enter fixed expenses when prompted
- Review budget allocation breakdown
- Choose to calculate another budget or exit

## Budget Allocations 
Savings: 25% of remaining income
Investments: 20% of remaining income
Emergency Fund: 15% of remaining income
Grocery: 15% of remaining income
Dining Out: 10% of remaining income
Transport: 5% of remaining income
Guilt-Free Spending: 10% of remaining income

## Output Format
- ASCII art header for visual engagement
- Formatted budget table using tabulate library
- Pie chart visualization saved as 'Budget_Allocation_Breakdown_PieChart.png'

## Error Handling
- Validates negative numbers
- Checks for invalid inputs
- Handles file operation errors
- Provides clear error messages

## Example of output
![output_example](https://github.com/user-attachments/assets/bdb3ea93-b49f-4fbf-ab08-c1f8a21c056c)


## Copyright and Licence 
    This project uses the following Python libraries:
    `matplotlib` (version 3.6.0) - Licensed under the [Matplotlib License](https://matplotlib.org/stable/users/license.html)
    - `tabulate` (version 0.9.0) - Licensed under the [MIT License](https://opensource.org/licenses/MIT)
    - `colorama` (version 0.4.6) - Licensed under the [MIT License](https://opensource.org/licenses/MIT)
    - `pyfiglet` (version 0.8) - Licensed under the [MIT License](https://opensource.org/licenses/MIT)

