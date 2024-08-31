# Email-Spam-Classifier-Using-TFIDI
Email Spam Classifier that is built using TF-IDF

->The program classifies the spam mails using TF-IDF(Term Frequency - Inverse Document Frequency).
->TfidfVectorizer works similar to TfidfTransformer, which is converting a collection of raw documents to a matrix of TF-IDF features. But in Tfidftransformer, we will systematically compute the word counts, generate idf values and then compute a tfidf score or set of scores. In TfidfVectorizer we can directly derive vectors.
->TfidfVectorizer basically classifies features based on the count of the repitive words in a sentence in vectors and number of sentences containing a particular word in vectors.
->We used Logistic Regression model to fit.
