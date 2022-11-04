# NLP-AutoCorrection
Autocorrection, coming under the application of NLP, is an automatic data validation function commonly found in word processors and text editing interfaces. Its principal purpose is to correct common spelling or typing errors, saving time for the user. 
The main steps to building an autocorrection model are:
1.	Identify misspelled words
2.	Find strings that are N-edit-distance away from the misspelled word. There are 4 different types of edits: Insert, Delete, Switch, Replace
3.	Filtering suggested candidates
4.	Order filtered candidates based on word probabilities
5.	Choose the most-likely candidate
