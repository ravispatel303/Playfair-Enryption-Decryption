# Playfair-Enryption-Decryption
Playfair Encrpytion and Decrytion Code in C program

What is Playfair ?
The Playfair cipher or Playfair square or Wheatstone-Playfair cipher or Wheatstone cipher is a manual symmetric encryption technique.
The technique encrypts pairs of letters (bigrams or digrams), instead of single letters as in the simple substitution cipher.

CODE EXPLANATION:

1. HOW KEY IS USED IN 5X5 BOX? 

  1.Convert alphabet j into i in key

  2.Remove repeatable alphabets from key 
  
  3.Modified key is the key which we got after replacing j with i and removing repeated alphabets.
  
  4.Assign first key in 5x5 matrix and then assign remaining alphabets in sequence from A to Z make sure that no alphabet is repeated in
    matrix.

2. HOW PLAIN TEXT WORKS?
  
  1.Convert alphabet j into i in Plain Text
  
  2.It will divide plain text into modules and each modules contains 2 letters (order should be maintained).
  
  3.It checks whether both the letters are same in each module.If yes then it will add dummy charachter(Here i have used X) and then again
    check whole procedure from 2.2 
  
  4.After 2.3 is completed it will check whether plain text length is odd or not if it is odd then concate dummy character(X) at last.
 
