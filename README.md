# ESEP_EC // In-Memory Database Project

## Overview

This Python project implements an in-memory key-value database with transaction support. It allows users to begin a transaction, perform operations like putting key-value pairs, and either commit these changes to the main database or rollback to the previous state.

## Setup and Running the Code

### Requirements

- Python 3.x

### Instructions

1. **Clone the Repository**: First, clone this repository to your local machine using `git clone https://github.com/ChandlerWiggins/ESEP_EC.git`.
2. **Navigate to the Project Directory**: Change into the project directory.
3. **Run the Program**: Execute the script by running:
   ```bash
   python memDB.py
   
## How to Modify This Assignment for Official Use

To enhance this assignment for academic purposes, several modifications could be considered:

- **Include Concurrency Support**: Modify the assignment to support concurrent transactions, introducing complexity that deals with race conditions and locking mechanisms.
- **Automated Testing**: Provide a framework for automated unit tests that students can run to verify their implementations independently. This would help in grading by having consistent criteria that assess functional correctness and error handling.
- **Enhanced Documentation**: Require students to document their code comprehensively, explaining their design choices and the implications of these choices on the behavior of the database.
