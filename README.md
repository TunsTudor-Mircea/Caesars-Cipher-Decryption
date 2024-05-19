# Caesar's Cipher Decryption

### Problem Description
Using frequency analysis to break Caesar’s Cypher.

This is a brute force method that tests all the possible displacements and returns the most likely decryption of a text.

Frequency analysis relies on the fact that some letters (or combination of letters) occur more in a language, regardless of the text size. 

For example, in English the letters E, A are the most frequent, while the Z and Q are the least frequent.

&nbsp;

## Features

* Computing a histogram of your message

*  Permuting the message by a degree

* Get the key for decrypting your message using Caesar's Cypher


&nbsp;


## Installation

Open the terminal, navigate to the desired location of the project using cd and clone the repository using the following command:
```bash
 git clone https://github.com/TunsTudor-Mircea/Caesars-Cipher-Decryption.git
```

&nbsp;


## Using the app

Run the CaesarsCypherDecrypt.exe file, found at:
> "...\CaesarsCipherDecrypt\CaesarsCipherDecrypt.exe"

#### Then pick through the following options:

[1] Enter a message

[2] Compute a histogram of your message

[3] Permute the message by a degree

[4] Get the key for Caesar's Cypher


###### To decrypt a text, input the encrypted message, get the key, then permute the message by that key

### Example

If you try to decrypt the message "L olnh wr zhdu kdwv.", you should reach the following text:  
"I like to wear hats."
#
