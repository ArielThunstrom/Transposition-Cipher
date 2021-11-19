# Mathematical Analysis
* How many possible keys or codes could there be? 
  * The numbers of possible keys really depends on the length of the key. For example, if the key has a lenght of 2, then there are only 2 different keys that could have been used to encrypt the message. However, if the key lenght is a larger number, like 10, then there could be 3,628,800 possible keys. The number of keys is always the factorial of the length of the key. 
* How would you attempt to decode this message if you didn't have a key?
  * In order to decipher a Transposition Cipher without the key you must first figure out the length of the key that was use. Without figuring out the length of the key, it is almost impossible to decrypt the code. To figure out the lenght of the key, you must test different lengths and find a length that looks like each coloumn might match up. There is no way to ensure that you have the correct length, you just need to use trail and error. Once you have a key length picked out, start to move around the columns until parts of the text starts to make sense.  
* What is the mathematical complexity to solve the code?
  * As mentioned before, if you are given the lenght of the key then the possible number of keys is !N, or the factorial of the length. This means that as the lenght of the key increases, so does the number of possible keys that could have been used. The longer the lenght of the key the more secure the message will be because a brute force attack on a key length of 100 would take a very long time because the factorial of 100 is an extremely large number. 

Here is an example of a this cipher in action:
![images](https://user-images.githubusercontent.com/94394689/142663982-aa9f0db5-f2bd-4466-a9fc-c1fc525fb752.jpg)


This website has some easy to understand examples of how to encrypt a message using a Transposition Cipher: https://en.wikipedia.org/wiki/Transposition_cipher
