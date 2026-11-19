# Barbaso_DeadlineDateFormatter
This program cleans user-submitted student details and formats event deadlines clearly using built-in Python string methods and the datetime module.  ## Language Used Python 3

# Student Event Registration Formatter

## Description
This program cleans user-submitted student details and formats event deadlines clearly using built-in Python string methods and the datetime module.

## Language Used
Python 3

## String Features Used
- `strip()`: Removes accidental leading and trailing spaces from messy text inputs like names, sections, and event titles.
- `title()`: Capitalizes the first letter of each word in the student's full name, section, favorite subject, and event title.
- `upper()`: Converts the student's full name into all-uppercase letters to generate a standardized name code.

## Date/Time Features Used
- `datetime`: Creates structured date and time objects from the event's year, month, and day values.
- `strftime()`: Formats the `datetime` object into readable text, such as the full month name (`%B`), formatted date (`%B %d, %Y`), and day of the week (`%A`).

## Version History
- Version 1: Initial version with basic input and unformatted date output.
- Version 2: Added built-in string methods (`strip()`, `title()`, and `upper()`) to clean and standardize messy text inputs.
- Version 3: Integrated the `datetime` module and `strftime()` to display event dates and weekdays in a clear, readable format.
