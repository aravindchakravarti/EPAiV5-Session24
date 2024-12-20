
# EPAiV5-Session24
Exceptions

![Build Status](https://github.com/aravindchakravarti/EPAiV5-Session24/actions/workflows/python-app.yml/badge.svg)

# Library Management System

## Overview

This project implements a **Library Management System** using **Enumerations** for book genres and membership levels. Custom exceptions are used to handle various error scenarios. The system includes classes for `Book` and `Member`, and a set of unit tests to ensure functionality.

## Features

- **Enumerations**:
  - `BookGenre`: FICTION, NON_FICTION, SCIENCE, HISTORY, BIOGRAPHY
  - `MembershipLevel`: BASIC, PREMIUM, GOLD

- **Custom Exceptions**:
  - `BookNotAvailableError`
  - `InvalidMembershipError`
  - `LateReturnError`

- **Classes**:
  - `Book`: Represents a book with attributes like title, genre, and availability.
  - `Member`: Represents a library member with attributes like name and membership level.

## Requirements

- Python 3.10 or higher
- `pytest` for running unit tests

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/library-management-system.git
   cd library-management-system
   ```

2. Install dependencies:
   ```sh
   pip install pytest
   ```

## Usage

### Running the Tests

To run the unit tests, use the following command:
```sh
pytest
```

### GitHub Actions

A GitHub Actions workflow is set up to run the tests automatically on push or pull request to the `main` branch. The workflow file is located at `.github/workflows/test_library.yml`.

## Project Structure

- `library_system.py`: Contains the implementation of the `Book` and `Member` classes, enumerations, and custom exceptions.
- `test_library_system.py`: Contains the unit tests for the library system.
- `.github/workflows/test_library.yml`: GitHub Actions workflow for running tests.

