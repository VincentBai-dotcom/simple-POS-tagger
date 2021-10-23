How to run the tagger:

In command line, go to the directory where the tagger program belongs, make sure you have three files in the same directory:

1. A trainer file
2. A test file
3. A blank solution file named "solution.pos" (Create one if you don't have one)

Then, run the following command:

python3 hb2385_HW3.py name_of_trainer name_of_test_file

The results will be stored in solution.pos.


OOV items:
I simply set the default probability of the word to be 1/1000 regardless of the tag, so that the result will be calculated based purely on the previous tag.


