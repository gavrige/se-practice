# se-practice
Financial Manager

Need: Managing finances
Who: Average joe
What: Inputting Transactions, searching and filtering transactions, keeping track of assets and liabilities.
How: Inserting and updating financial information on a regular basis, using tools to look through the information to see patterns and trends.


Transactions come in as an inputstream from the users bank and are converted to a string which is broken up into transaction time, place and amount of money spent which are used to create an instance of the transaction object. This transaction object is passed into an instance of a transaction trie class that sorts transactions based on the string of their location, where at each “hit” there is a node that stores an arraylist of transactions that happened at that location. The user can then use advanced search methods in the financial manager class to search for transactions grouped by the amount, date or location of the transaction. 
 