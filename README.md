# BizOps Loan Application Qualification
Software that allows user to verify their loan qualification using a prompt dialog to get the users financial information, and Allows the user to save the result in a csv file 



---

## Technologies

- Python 3.8.5
- fire==0.4.0
- questionary==1.10.0

---

## Installation Guide

1. Navigate to the folder LOAN_QUALIFIER_APP directory:

        cd "path to the LOAN_QUALIFIER_APP" 

2. Install dependecies packages run:

        pip install -r requirements.txt

---

## Usage

1. To Run the application type in your terminal or cmd:

        python app.py


2. Then the app will prompt you for a path to csv file
    > you can use the default csv file that is in the data folder using the path data\daily_rate_sheet.csv

        Enter a file path to a rate-sheet?
        Enter a file path to a rate-sheet (.csv): data\daily_rate_sheet.csv

3. Then the app will propmt you for the credit score information:

        What's your credit score?

4. Then enter your monthly deb.

        What's your current amount of monthly debt?

5. Then enter your monthly income

        What's your total monthly income?

6. Then enyer the disere loan amount

        What's your desired loan amount?

7. Enter the  home value

        What's your home value??

8. Then the app will print the information of the deb to income ratio, loan value ratio and the number of qualifying loans

        The monthly debt to income ratio is 0.05
        The loan to value ratio is 0.60.
        Found 18 qualifying loans

9. Then the app will ask the user if they want to save the result in a csv file
    > In case user select No or other message the app will promp a goodbye message

        Whould you like to save your qualifyng loan (YES or NO)?

 10. Enter the path that you want to save the new csv file:
    
         "Path to the new CSV File"      

 11. Finally the app will prompt a message went start creating the csv file and went is done.

         Saving your file please wait...
         Operation completed have a nice day!
---

## Contributors

In this section, list all the people who contribute to this project. You might want recruiters or potential collaborators to reach you, so include your contact email and, optionally, your LinkedIn or Twitter profile.

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
