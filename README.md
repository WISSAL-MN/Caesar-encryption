# Caesar message encryption and decryption program in python3.
----

1. First we give a list of lowercase alphabets and a list of uppercase alphabets.

2. We go through the whole alphabet and learn the lowercase alphabet and the uppercase alphabet with each journey.

3. Then we have our encryption function which takes as parameter the message, the lowercase alphabet, the uppercase alphabet and the offset it goes through the whole alphabet and evaluates certain conditions such that if the letter is a space it returns a space , and if the message letter is a lowercase alphabet it applies the shift to the lowercase letter and returns the result, and finally if the message letter is uppercase it applies the shift to the uppercase letter and returns the result otherwise it's a symbol, so it returns the symbol.

4. After we create a string called message number for each test set and we use a loop that will go through our message letter by letter and give encrypted message each letter encrypted using the function encryption message created previous which will take in parameter letter, alphabet, alphabet2 and our offset previously entered by the user, and finally we will display our encrypted message.

5. Then we create a string called message_encrypted and we use a loop that will go through our encrypted message_letter by letter and give message_decrypted each letter decrypted using the previously created encryption_message function which will take the same thing as before as parameter but just with the offset in negative, and finally we will display our decrypted message.

