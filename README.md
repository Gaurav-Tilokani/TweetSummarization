# TweetSummarization
Finetuned Pegasus model for accurate abstractive summarization of tweets.

Technologies Used: Python

Preprocessing: Used Tweet preprocessor library which handles URLs, mentions, reserved words, emojis, etc.

Pretrained Language Model: Pegasus Large.

Tokenizer: Pegasus tokenizer

Finetuning of Model:
  Freezing Layers: By freezing layers weights of that layer donot change during training this minimizes computational time for training model.

Model Evaluation: Rouge Score
  RougeL : 39.67
  RougeLsum : 39.51
  
