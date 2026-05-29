
📘 Checking Driving Eligibility
===============================

A beginner Python project that checks driving eligibility based on the user's age and driving license status. This project demonstrates the use of user input, conditional statements, and basic decision-making in Python.

---------
🎯 Purpose
---------

* Determine whether a candidate is eligible to drive based on age, country-specific driving laws, and license status

* Demonstrate the use of Python concepts such as loops, conditional statements, dictionaries, and exception handling

* Simulate a real-world driving eligibility verification system

* Improve understanding of input validation and rule-based program logic

----------
🎯 Features
----------

* Accepts user input for country, age, and license status

* Applies country-specific minimum driving age rules

* Verifies driving eligibility based on legal requirements

* Validates driving license or permit status

* Prevents invalid or unrealistic age inputs

* Handles unsupported countries gracefully

* Uses exception handling for invalid input types

* Continuously runs using a while loop until the user exits

* Provides a restart option for repeated checks

* Supports case-insensitive user input handling


--------------
🚀 Concepts and principles used
--------------

### Receive user input:
The program uses the input function to obtain the user’s age and driving license status for evaluation.
### Country filter:
Different countries have different legal driving age requirements, so the minimum age for driving eligibility is dynamically determined based on the user’s selected country.  
### Conditions
If either input or both inputs do not satisfy the driving eligibility rules, the program displays a message stating that the candidate is not eligible to drive.
### Starting message
After displaying the result, the program prompts the user to restart the process. If the user responds yes, the while loop continues, and the input sequence is repeated. If the user responds no, the loop breaks and the program terminates gracefully with exit code 0.

------------
🚀 Tools used
------------

Python
IDE used - PyCharm

---------------------------------------
📘 How can it be improved in the future?
---------------------------------------

### 🔐 1. Add attempt limits for input errors
  Stop infinite retries for invalid inputs
  Example: allow only 3 invalid attempts before exiting
### 🌍 2. Expand country database
  Instead of just India/US/UK:
  Add more countries (Canada, Australia, Germany, etc.)
  Store rules in a dictionary (you’re already doing this 👍)
### 🚗 3. Add vehicle type selection
  Different rules for:
  1. Bike 🏍️
  2. Car 🚗
  3. Heavy vehicle 🚛
  Each can have different minimum age requirements.
### 📊 4. Improve output clarity (status system)
  Instead of only printing text, use structured results:
  “ELIGIBLE”
  “NOT ELIGIBLE”
  “REQUIRES TEST”
  Makes it look like real software output.
### 🧠 5. Add a rule explanation feature
  After the result, show why:
  For example: “Reason: Age below minimum requirement for India (18 years).”
### 🕒 6. Add a logging system
  Save results like:
  username/age/country/result
  This makes it feel like a real database system.
### 💾 7. Store data in a file
  Save results in .txt or .csv
  So history is preserved after the program ends
### 🔁 8. Improve the loop system (clean exit control)
  Instead of multiple break conditions:
  Use a proper menu system (Login / Check / Exit style)
### ⚡ 9. Improve input validation
  Block empty input
  Handle wrong strings more strictly
  Avoid crashes for unexpected input types
### 🎨 10. Make UI cleaner (developer-level polish)
  Add spacing and headings
