# oibsip_4
<h1>EMAIL SPAM DETECTION WITH MACHINE LEARNING</h1>

<p>To detect the spam messages using machine learning techniques</p>
<p>Datset Credits : https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset </p>

![Screenshot (111)](https://user-images.githubusercontent.com/100411386/222920173-c8efafd5-6efb-442c-bd53-09d1287a5741.png)

<h1>Model :</h1>
<p><b>Multinomial Naive Bayes algorithm (MNB)</b> is a probabilistic learning method that is mostly used in Natural Language Processing (NLP).</p>
<p> The <b>MNB algorithm</b> works on Bayes Theorem, which calculates the probability of an event occurring based on the prior knowledge of conditions related to an event :</p> <p>P(A|B) = P(A) * P(B|A)/P(B)</p>
<p>I have choosen the <b>MNB algorithm</b> as its precision is better and in this type of problem precision matters more than accuracy</p>
<p>Precision : 1.0</p>
<p>Confusion Matrix :  [[896   0]
                        [ 42  96]]</p>
<p>Accuracy : 0.9593810444874274</p>

<h1>About Data :</h1>
<p>Most occuring words in a <b>Spam messages</b> in the data :</p>

![span messages](https://user-images.githubusercontent.com/100411386/222920701-991fff8a-aea0-4dfa-bd4f-078257464a78.png)

<p>Most occuring words in a <b>not Spam messages</b> in the data :</p>

![not spam messages](https://user-images.githubusercontent.com/100411386/222920723-3b82f0f4-aceb-4ca4-b637-afe2d63c409b.png)

<h1>Natural Language Processing (NLP) techniques used :</h1>
<p><b>1. LowerCase Conversion :</b> Converting every letters in lowercase </p>
<p><b>2. Word tokenization :</b> Converting the sentences into list of words</p>
<p><b>3. Stop Words Removal :</b> Removing the stop words from data which do not adds meaning to the sentences like the, a, this, etc..</p>
<p><b>4. Stemming :</b> Converting the words with same/similar meaning into its base form</p>


