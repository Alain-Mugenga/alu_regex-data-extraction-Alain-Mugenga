Regex Validator – Python Script Welcome to this simple yet handy Python script designed to validate common data formats using Regular Expressions (regex). If you're dealing with email addresses, URLs, phone numbers, or currency values and want a quick way to check their validity, this script has got you covered.

1.What It Does:
 *This script uses Python’s re module to validate:

Emails (e.g. user@example.com)

URLs (e.g. https://www.example.com)

Phone Numbers (e.g. (123) 456-7890, 123-456-7890, etc.)

Currency Amounts (e.g. $1,234.56)

 *It also includes a test suite with sample inputs and prints whether each example is valid or not.

2.File Overview: RegexExtraction.py

*is_valid_email(email) – Checks if an email address is valid.

*is_valid_url(url) – Checks if a URL is valid.

*is_valid_phone(phone) – Checks if a US-style phone number is valid.

*is_valid_currency(amount) – Checks if a currency string follows the $X,XXX.XX format.

*A sample dictionary test_data with various examples.

*For-loops that run validations on the test data and print out results.

3.How to Run Make sure you have Python installed (3.x).

4.Clone this or download the file.

5.Open a terminal and run:

bash Copy Edit python RegexExtraction.py You'll see output showing which entries passed or failed validation
