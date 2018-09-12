# Working Process
Initially user has 1000 INR balance, whenever user clicks on the Start button a 3-digits random number will be generated,
and his/her balance will be deducted by 100 INR.
If all the 3-digits are same user will get 1000 INR,
If all the 3-digits are odd/even user will get 300 INR,
If all the 3-digits are consecutive no matter what their order is, user will get 800 INR.
User's balance will be updated by adding the winning amount.
If all the 3-digits are not as per the conditions mentioned above user needs to try again, if user's balance reaches below 100 INR, Game will be Over.

# Technologies Used
A function which is triggered when user hit the start button.
3-digits number is genereted by JS Math.random() fun, then digits are converted into a string and again that string is converted into array
using split('') method.
All the 3-digits are compared inside a else-if ladder.

# Others
Some CSS are applied to to the html elements:background, color, padding, margin, border, outline,hover,text-alignment etc..
