# GRADE THE EXAM
## Description
The program takes a file path that user specifies that contains information about students and their exam result. It checks for invalid data and returns a list of client and their overall score as the final output. 
## Usage
1. User shall be prompted to provide the path to the exam result files. The file must be in comma-separated format, with eachline starting with student number, followed by their answer to 25 questions on the exam.
2. The program first check if the file exists. If not, it will inform the user and request for re-submitting.
3. If the file exist, the program will then check for invalid data. Invalid data includes:
    * Too many or too few data on each line (there must be 1 student number followed by 25 answer for each line)
    * Wrong student number format: student number start with 'N' and then 8-digit number
  A message will be printed to summarize the number of invalid data lines, which line is invalid and the reason of invalidity
4. For the valid lines in the file, the program will produce the score of each students by comparing exam answer to the answer keys. Exam score will be calcualted for each student and statistical summary (average, max, mean, range and median) is returned.
5. In the same location of the input file, the program will produce an output file containing the student numbers and their score. The data is in comma-separted value format. 
## Status
```Finished```
