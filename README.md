# REVERSE_MD5_HASH
This application is used to reverse an MD5 hash using a brute force technique where we simply 'forward hash' all possible combinations of characters in strings. This would be similar to a situation where an e-commerce site stored hashed passwords in its database and we somehow have gotten our hands on the database contents and we want to take the hashed password and determine the actual plaintext passwords.

This application will take an MD5 value like "81dc9bdb52d04dc20036dbd8313ed055" (the MD5 for the string "1234") and check all combinations of four-digit "PIN" numbers to see if any of those PINs produce the given hash.
