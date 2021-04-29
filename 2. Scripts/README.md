This README describes the structure associated with the scripts for processing the TweetEval data sets for 'emotion', 'hate' and 'offensive'.

=== Code Desciptions ===

  The scripts for classification follow the same approach for all 3 categories of data: 'emotion', 'hate', 'offensive'. To run, open the scripts in Google Colab and 'run all'. Please make sure a GPU is enabled as the models are set to run on a CUDA.
  - data import
  - replacement of misspelled words
  - replacement of internet slang abbreviations
  - removal of HTML elements
  - removal of language contractions
  - conversion of emojis into text
  - removal of punctuation
  - removal of user mentions
  - mapping of tweets as per the TweetEval guidance
  - exploration of processed data
  - the outputs from each of the 3 scripts are located in folder '3. Datasets' of this repository
  - the RoBERTa Base and XLNet model set up, training and evaluation using the F1 Macro Averaged Score.
  - evaluation of results using normalised confusion matrices 
  
