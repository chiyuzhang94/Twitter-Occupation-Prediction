# Twitter Occupation Prediction Dataset

## Descriptions
1. twi.follow - user_id [SPACE] user_id
   each line represents an edge

2. twi.user_label - user_id [SPACE] label
   each line represents an user  and its label.  Label -1 is a dummy label.

3. twi.bio_vocab - word
   each line is a word from the top 5000 frequent words.

4. twi.bio_content_csr - a sparse matrix in scipy csr format (dim 34603 * 5000)
   each line of the sparse matrix represents the bag-of-words feature for corresponding user in twi.follow

5. train_val_test_id - index of users in training/validation/test corresponding to the first 4557 users in twi.user_label
   first 3645 indexes for training set, next 456 for validation set, and the last 456 for test set




