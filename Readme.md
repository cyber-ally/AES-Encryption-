# AES Encryption and Decryption

The project is about a standalone command line tool which encrypt and decrypt files.

* Specifications

The program encrypts diary.txt and writes the ciphertext into diary.txt.enc file using Advanced Encryption Standard.
The command line tool takes two 2 inputs: A mode and a Filename.
The mode is either 'e' or 'd' representing encrypt or decrypt. Below is the example of commands that are run to test the program.

encrypt360 e diary.txt

encrypt360 d diary.txt.enc

The bit of code uses the Pyhton os module to check that the filename given given as the 2nd input by the user refers to a file that really exists. If the file does not exist, the program shuts down.
