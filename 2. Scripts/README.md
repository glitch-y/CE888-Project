This README describes the structure associated with the scripts for processing the TweetEval data sets for 'emotion', 'hate' and 'offensive'.

=== Code Desciptions ===
  1. The preprocessing codes follow an identical approach as per below:
  - data import
  - replacement of misspelled words
  - replacement of internet slang abbreviations
  - removal of HTML elements
  - removal of language contractions
  - conversion of emojis into text
  - removal of punctuation
  - removal of user mentions
  - mapping of tweets as per the TweetEval guidance
  - exploration of mapped data
  - the outputs from each of the 3 preprocessing scripts are located in folder 3. Datasets of this repository
  - the RoBERTa Base and XLNet model set up, training and evaluation using the F1 Macro Averaged Score.
  
