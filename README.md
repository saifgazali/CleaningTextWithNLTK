# CleaningTextWithNLTK

Tokenization and Cleaning with NLTK

# Hashing with HashingVectorizer
Counts and frequencies can be very useful, but one limitation of these methods is that the
vocabulary can become very large. This, in turn, will require large vectors for encoding
documents and impose large requirements on memory and slow down algorithms. A clever work
around is to use a one way hash of words to convert them to integers. The clever part is that
no vocabulary is required and you can choose an arbitrary-long fixed length vector. A downside
is that the hash is a one-way function so there is no way to convert the encoding back to a word
(which may not matter for many supervised learning tasks).
