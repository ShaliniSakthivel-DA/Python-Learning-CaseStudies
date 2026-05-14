# Python Email Generator using String Manipulation

## Project Description
This is a beginner-friendly Python project that generates an email username from a user's full name using Python string methods.

The program:
- Takes the user's full name as input
- Converts the text to lowercase
- Replaces spaces with underscores
- Combines it with a domain name
- Displays the generated email address

---

## Features
- User input handling
- String manipulation using:
  - `lower()`
  - `replace()`
- Simple and easy-to-understand code
- Beginner Python mini project

---

## Technologies Used
- Python 3

---

## Sample Code

```python
# Email Generator

full_name = input("Enter Full Name: ").lower().replace(" ", "_")
domain_name = input("Enter Domain Name: ")

email = full_name + domain_name

print("Generated Email:", email)
```

---

## Example Output

```text
Enter Full Name: SHALINI SAKTHIVEL
Enter Domain Name: @gmail.com

Generated Email: shalini_sakthivel@gmail.com
```

---

## Author
Shalini Sakthivel
