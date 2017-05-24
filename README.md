# Storing Passwords Quiz
## Would you like salt with your hash?


With your partner, in words both of you will understand 6 months from now, answer the following questions.

> A customer hires you to consult on a web app.  You notice that they are storing their passwords in plaintext.  What advice would you give the customer.  This advice should outline the risks of the current solution, and give a list of best practices for a new solution.

Don't store passwords in plain text! It is risky because it is easy to see any passwords stored as plain text. Instead they should use a strong hashing algorithm and add salt to the end of each password.  

> You are tasked for creating a RFP (request for proposal) for a new cryptographic hashing algorithm.  What requirements would you put in place for this new algorithm.

1. It should be efficient but not too quick.
2. No two different passwords should result in the same hash.
3. Similar passwords should have very different hashes (avalanche effect).
4. Every hash should be the same length regardless of the length of the password.
5. The hashing algorithm should be one way.
