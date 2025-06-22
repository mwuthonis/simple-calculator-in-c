# simple-calculator-in-c

## How to Compile and Run

### Prerequisites
- [MinGW](https://www.mingw-w64.org/downloads/) (GCC) installed and added to your system PATH
- VS Code or any terminal

### Steps

1. **Open a terminal** and navigate to the project directory:
   ```
   cd "C:\Users\david\simple calculator app"
   ```

2. **Compile the program** (replace `calculator.c` with `test.c` to run the test file):
   ```
   gcc calculator.c -o calculator.exe
   ```

3. **Run the compiled program:**
   ```
   calculator.exe
   ```

   For the test file:
   ```
   gcc test.c -o test.exe
   test.exe
   ```

### Notes
- Make sure `gcc` is recognized in your terminal by running `gcc --version`.
- If you encounter issues, ensure MinGW's `bin` directory is in your system PATH and restart your terminal or computer if needed.