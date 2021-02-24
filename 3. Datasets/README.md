This README describes the format, file and directory structure associated with the preprocessed data sets for 'emotion', 'hate' and 'offensive', 
as per the TweetEval Git repository.

=== DIRECTORY STRUCTURE ===
  1. Emotion
  - mapped_emotion_test.csv
  - mapped_emotion_train.csv
  - mapped_emotion_val.csv
  2. Hate
  - mapped_hate_test.csv
  - mapped_hate_train.csv
  - mapped_hate_val.csv
  3. Offensive
  - mapped_offensive_test.csv
  - mapped_offensive_train.csv
  - mapped_hate_val.csv

=== FILE FORMAT ===

Each file has one tweet per line in the preprocessed format. Each file has one ID, one label and one description of the label per line 
which maps to its corresponding tweet. 

=== LABELS ===

 - Emotion Recognition - 4 labels: anger, joy, sadness, optimism
 - Hate Speech Detection - 2 labels: hateful, not hateful
 - Offensive Language Identification - 2 labels: offensive, not offensive

