# Mechanics
## How does the cipher work? 
* Transposition cipher rearranges the plain text letters in a new order.

![Screen Shot 2021-11-19 at 2 30 11 PM](https://user-images.githubusercontent.com/72951482/142700409-e2990f69-89ff-43f6-8a86-9d97e92a2462.png)

* To encrpt: Take the key (it would have to be a combination of letters). Each letter of the key will get a value starting from one. Then you would put the key in alphabetical order with the value attached to it. So, if "KEY" was the key it would get the value of 2 1 3. Then you make the columns with the length of the key. You would then go through each box writing a letter in it. The amount of rows will be decided when you run out of letters. If there is extra space in the row, add an "X". Now using the key, rearrange the letters in each row. For example, if the plaintext was "CAKE", then on the first row with the key being "KEY" it would be ACK. The second row would be XEX. Now you would go down each column. This would give you the ciphertext.

* To decrypt: You would put the ciphertext back in the table first and then write the key value on top for reference. Then you would rearrange the letters by looking at the key value starting from 1. For example, the key ("KEY") has the value 2 1 3 and the plaintext is "CAKE" with the first row of the table being ACK and the second row being XEX. When looking at the key and rearranging it accordingly starting from 1, it would be C (1) A (2) K (3) for the first row. 

## Is it symmetric, does the same process decrypt as encrypt?
It is symmetric because even though the algorithms for encryption and decryption are different, the same key is used. The decryption key can be derived from the encrption key.

[Click here for more information](https://www.dcode.fr/transposition-cipher)
