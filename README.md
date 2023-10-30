# sorting-and-searching-algorithm

This is an insertion sort algorithm for a deck of cards.
A deck 0f cards consist of 52 cards that would be placed in an array.

# Summary of the code

1.  Lines 1 defines the insertion sort algoritm.
2.  Lines 2 - 4 defines the variables to be used
3.  Lines 7 - 10 Asks the user for the number of card they intend sorting min of 0 and a max of 52 (Number of cards in a deck)
4.  Lines 13 - 16 Asks the user to input the values of the card. This is then passed into an array (arr) using a FOR loop.
5.  Lines 19 is a FOR loop used for iterating through the unsorted part of the array.
6.  Lines 20 stores each number to insert from each iteration in the variable numberToInsert.
7.  Lines 21 targets the sorted portion of the array.
8.  Lines 22 - 25 iterates through the sorted array: It compares the number of sorted elements in the array with the number to insert while trying to find where the insertion will take place. The index is where sorted elements is lesser than the number to be inserted.
9.  Lines 26 the number is then inserted to the right of the sorted array.
