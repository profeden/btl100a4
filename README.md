# Activity 4 (GitHub Activity)

In this activity, you and a partner (optionally), write a pair of C functions that encrypt and decrypt a string. 

## Specifications

1.  a skeleton of a file structure is given
  - `encrypt.h`, includes the signature for the encrypt and decrypt functions that a user would invoke
  - `strutil.h`, includes signature for string manipulation functions
  - `translationtable.h`, includes constant arrays required for translation, each lower case character is somehow mapped to an encyption character
  - `main.cpp`, includes program you will write to invoke encrpyt and decrypt functions

2. In the initial version of your solution,
  - the encrypt function shall
      - call strutil functions to remove non-alpha characters, and convert the string passed in to lower case
      - use translationtable constants to construct the encrypted string from the original on a character by character basis 
      - not modify the input string
      - return the encrypted string to the user
  - the decrypt function shall
      -  use translation table constants to construct the decrypted string using an inverse operation on the input string
      -  not modify the input string
      -  return the decrypted string to the user
  -  the main function shall 
      - call the encrypt and decrypt functions with test data to ensure that they work correctly  

3. Implement a different encpytion scheme on a *new branch*
  - encryption/decryption must be modulus 26 based.  Each character would be mapped to a value between 0 and 25. This would be used instead of an explicit table approach used above


## Notes

- You should incrementally build your solution, committing added/modified content as you build,  changes should be committed to the repository by the author who wrote them
- Each change committed should have an associated relevant message.
- Implementations to signatures defined in header files should be placed in corresponding .c files as per convention (these must be added).
- Comment solution as you were taught in your programming course.
- Late submissions will not be eligilble for bonus marks.





