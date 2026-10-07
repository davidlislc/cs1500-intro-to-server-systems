# cs1500 scripting2

**1. Which of the following syntaxes is valid for a test expression in a shell script?**

- A) test EXPRESSION
- B) [ EXPRESSION ]
- C) [[ EXPRESSION ]]
- D) All of the above

**2. Which test syntax is preferred for new scripts because it supports features like wildcards and regex?**

- A) test
- B) [ ... ]
- C) [[ ... ]]
- D) ( ... )

**3. What is a critical requirement when using the [ ] syntax for tests?**

- A) No spaces allowed
- B) A space must follow '[' and precede ']'
- C) Must always use single quotes
- D) Only works for numeric comparisons

**4. In a shell script, what does the variable '$0' contain?**

- A) The first parameter
- B) The process ID
- C) The name of the script
- D) The number of parameters

**5. Which variable represents the number of command line parameters passed to a script?**

- A) $*
- B) $#
- C) $@
- D) $?

**6. What does the '$?' variable represent?**

- A) The process ID of the shell
- B) The last command's return (exit) code
- C) All parameters as a list
- D) The second parameter

**7. Which string test returns true if the string is null (empty)?**

- A) -n string
- B) -z string
- C) string1 == string2
- D) string1 != string2

**8. What is the correct operator for 'Greater than' in a numeric comparison?**

- A) -gt
- B) -ge
- C) -lt
- D) -ne

**9. Which operator is used to test if two integers are NOT equal?**

- A) -eq
- B) -ne
- C) -le
- D) -lt

**10. How do you test if a specific path is a directory?**

- A) -f file
- B) -e file
- C) -d file
- D) -s file

**11. Which file enquiry operation tests if a file exists?**

- A) -x file
- B) -w file
- C) -r file
- D) -e file

**12. What does the '-x file' operator check for?**

- A) If the file is readable
- B) If the file is writable
- C) If the file is executable
- D) If the file is owned by the user

**13. Which operator tests if a file has a non-zero length?**

- A) -z file
- B) -s file
- C) -f file
- D) -o file

**14. What is the correct syntax for performing arithmetic expansion in Bash?**

- A) [ expression ]
- B) (( expression ))
- C) $(( expression ))
- D) { expression }

**15. What is the result of the arithmetic expansion $(( 10 / 5 ))?**

- A) 50
- B) 15
- C) 2
- D) 0

**16. Which operator provides the remainder (modulus) of a division?**

- A) /
- B) *
- C) %
- D) -

**17. What is the result of $(( 10 % 5 ))?**

- A) 2
- B) 0
- C) 5
- D) 1

**18. Which variable contains the process ID of the shell?**

- A) $#
- B) $*
- C) $$
- D) $?

**19. Which positional parameter represents the 2nd command line parameter?**

- A) $0
- B) $1
- C) $2
- D) $@

**20. In a conditional statement, which keyword is used to close the 'if' block?**

- A) end
- B) stop
- C) fi
- D) done

