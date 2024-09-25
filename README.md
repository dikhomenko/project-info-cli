# project-info-cli

This personal assistant is an application that allows you to easily manage your contacts and notes. Thanks to it, you can quickly add, edit and delete contacts, as well as save important notes and perform various actions with them.

## Requirements

To use the program, you must have Python 3.x installed on your computer.

## Installation

## Встановлення

1. Clone the repository to your computer:
   git clone https://github.com/dikhomenko/project-info-cli.git

2. Go to the directory with the project:
   cd project-info-cli

3. Run the following command in Terminal to build and install the app:
   python3 setup.py build --build-lib=. && python3 setup.py install

## How to use

1. **Manage contacts:**

- Add new contacts using the `add-contact` command.
- Delete contacts using the `delete-contact` command.
- Edit phone numbers for contacts using the `change-phone` command.
- View the list of all contacts using the `all-contacts` command.
- There is also an option to add and view other contact details such as address, email and date of birth.

2. **Manage notes:**

- Add new notes using the `add-note` command.
- Edit the contents of notes using the `change-note` command.
- Delete notes using the `delete-note` command.
- View a list of all notes using the `all-notes` command.
- It is possible to add and search for notes by tags.

## Important

Changes to your contact list and notes will be saved automatically when you exit the program.

## License

This project is licensed under [MIT License](https://opensource.org/license/MIT).

## Contact information

If you have any questions or suggestions, please feel free to contact us by any means.
