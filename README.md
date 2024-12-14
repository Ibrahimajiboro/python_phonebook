# Control Management System

A simple command-line interface (CLI) application for managing contacts.

## Overview

This Contact Management System is a Python-based application that allows users to add, edit, delete, and search for contacts. It provides a user-friendly interface for managing personal or professional contact information.

## Features

- Add new contacts with name, address, multiple phone numbers, and email addresses
- Edit existing contact information
- Delete contacts
- Search for contacts by name
- Display contact details

## Usage

To run the Contact Management System:

1. Ensure you have Python installed on your system.
2. Download or clone the repository.
3. Run the script using Python:

```
python contact_management.py
```

4. Follow the on-screen prompts to manage your contacts.

## Menu Options

The application provides the following menu options:

1. Add Contact
2. Edit Contact
3. Delete Contact
4. Search Contact
5. Exit (Enter '#')

## Adding a Contact

When adding a new contact, you'll be prompted to enter:
- Name
- Address
- Phone number(s)
- Email address(es)

You can add multiple phone numbers and email addresses for each contact.

## Editing a Contact

The edit function allows you to:
- Modify the address
- Add, edit, or delete phone numbers
- Add, edit, or delete email addresses

## Data Structure

Contacts are stored in a dictionary with the following structure:

```python
contacts = {
    "name": {
        "add": "address",
        "phones": ["phone1", "phone2", ...],
        "emails": ["email1", "email2", ...]
    }
}
```

## Error Handling

- The system prevents duplicate contact names.
- After three invalid menu selections, the program will exit due to a "Technical Issue".

## Future Improvements

- Implement data persistence (save contacts to a file or database)
- Add sorting and filtering options for contacts
- Implement a graphical user interface (GUI)
- Add contact groups or categories

## Contributing

Contributions to improve the Contact Management System are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to all contributors who have helped with this project.
- Inspired by the need for a simple, customizable contact management solution.
