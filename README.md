# Name Management Software

This is a **name management software** developed in JavaScript to handle operations like adding, listing, verifying, and removing names from a dynamic list.

## Features

- **Add Person**: Adds a name and age to the list.
- **Validate Fields**: Ensures all fields are filled out before adding a new person.
- **List People**: Checks if the provided name exists in the list and returns its index if found, or informs that the name was not found.
- **Remove Person**: Removes a specific name from the list if it exists.
- **Confirm Action**: Verifies fields before executing the functionality to list or remove a person.

## Code Structure

- `adicionarPessoa()`: Adds a person (name and age) to the list.
- `verificarCampos()`: Validates input fields before calling the add function.
- `listarPessoas()`: Searches for the name in the list and provides feedback whether found or not.
- `removerPessoa()`: Removes the name from the list if found.
- `verificarRemoção(funcao)`: Checks the input fields before invoking listing or removing functionality.

## How to Use

1. Fill in the **Name** and **Age** fields and click the add button to include a person in the list.
2. To verify or remove a person, enter the name in the corresponding field and choose the desired action:
   - **List**: Check if the name exists in the list and return its index.
   - **Remove**: Delete the name from the list if it exists.

## Notes

- Make sure to fill in all required fields before performing any operation.
- The software uses an array `pessoas` to store the data in memory.

---