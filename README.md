# question-no-3403
Solution to the question no 3403 on leet code 

3403. Find the Lexicographically Largest String From the Box I
You are given a string word, and an integer numFriends.

Alice is organizing a game for her numFriends friends. There are multiple rounds in the game, where in each round:

word is split into numFriends non-empty strings, such that no previous round has had the exact same split.
All the split words are put into a box.
Find the lexicographically largest string from the box after all the rounds are finished.

If numFriends == 1, return the whole word.

Otherwise:

From each position i, take a substring of length n - numFriends + 1

Keep track of the largest (lexicographically) among these substrings.

Return that largest substring.

