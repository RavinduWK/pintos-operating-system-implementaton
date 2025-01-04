# README

## Project: Pintos Lab 2 - Phase 1

This repository contains test cases and necessary files to validate the functionality of the Pintos operating system for Lab 2 - Phase 1.

### Directory Structure

- **DFSIGNDOC**: Contains documentation and screenshots of test cases.
- **pintos-Lab2-phase1**: Main directory for the Pintos project.
- **Test Cases**: Each folder contains specific tests to be run in the Pintos environment.

### Prerequisites

Ensure you have the following installed on your Linux machine:

1. GNU Make
2. GCC (GNU Compiler Collection)
3. Bochs Emulator (if running Pintos tests in a virtual environment)
4. Necessary dependencies for the Pintos framework

### Running the Tests

Follow these steps to compile and run the tests:

1. **Navigate to the `pintos-Lab2-phase1` Directory**:

   ```bash
   cd pintos-Lab2-phase1
   ```

2. **Go to the Folder You Want to Test**:
   Navigate to the specific folder containing the desired tests, for example:

   ```bash
   cd tests/<test-folder>
   ```

3. **Build the Tests**:
   Compile the test cases using the `make` command:

   ```bash
   make
   ```

4. **Navigate to the Build Directory**:

   ```bash
   cd build
   ```

5. **Run the Tests**:
   Execute the tests by entering the following command:
   ```bash
   make check
   ```
   This will run all the test cases in the specified folder and output the results in the terminal.

### Output

- The test results will be displayed in the terminal and saved in the `build` directory logs.
- Review the logs for detailed information on passed and failed test cases.

### Notes

- Ensure you have all dependencies installed and properly configured.
- Refer to the screenshots in the `DFSIGNDOC` folder for visual reference and troubleshooting.
- If you encounter issues with the emulator, consult the Pintos documentation for configuration settings.
